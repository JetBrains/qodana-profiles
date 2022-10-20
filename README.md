# qodana-profiles

[![official JetBrains project](https://jb.gg/badges/official.svg)][jb:confluence-on-gh]
[![GitHub Discussions](https://img.shields.io/github/discussions/jetbrains/qodana)][jb:discussions]
[![Twitter Follow](https://img.shields.io/twitter/follow/Qodana?style=social&logo=twitter)][jb:twitter]

Code inspection profiles that are included in each Qodana Docker image. Published on GitHub for the reference.

## Project structure

Each Qodana Docker image has own branch in this repository. ```.idea/inspectionProfiles/*.xml``` are copied into corresponding Docker image as embedded IDE profiles.

- Each profile should have proper name in structure ```<option name="myName" value="%profileName%" />```
- Profile could be referenced in ```qodana:dev``` image as ```%profileName%```
- Profiles in branches for public images should have prefix ```qodana.```

[youtrack]: https://youtrack.jetbrains.com/issues/QD
[youtrack-new-issue]: https://youtrack.jetbrains.com/newIssue?project=QD
[jb:confluence-on-gh]: https://confluence.jetbrains.com/display/ALL/JetBrains+on+GitHub
[jb:discussions]: https://jb.gg/qodana-discussions
[jb:twitter]: https://twitter.com/Qodana
[jb:docker]: https://hub.docker.com/r/jetbrains/qodana

## Issue Tracker

All the issues, feature requests, and support related to Qodana are handled on [YouTrack][youtrack].

If you'd like to file a new issue, please use the link [YouTrack | New Issue][youtrack-new-issue].
