# sa/qodana-embedded-profiles

Idea profiles for embedding to qodana docker image

## Project structure
Each qodana docker image should have own branch in this repo. 
```.idea/inspectionProfiles/*.xml``` are copied into corresponding qodana docker image as embedded IDE profiles.
Each profile should have proper name in structure ```<option name="myName" value="%profileName%" />```, 
profile could be referenced in ```qodana:dev``` image as ```%profileName%```.
Profiles in branches for public images should have prefix ```qodana.```

## Deployment

Add additional notes about how to deploy this on a production system.

## Resources

Add links to external resources for this project, such as CI server, bug tracker, etc.
