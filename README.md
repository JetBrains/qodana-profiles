# sa/qodana-embedded-profiles

Idea profiles for embedding to qodana docker image

## Project structure
Each qodana docker image should have own top level directory. 
Top level directories contains profile files, profile file could be stored under subdirectories.  
Profile ```dev/php/qodana.php.default.xml``` could be referenced in ```qodana:dev``` image as ```php/qodana.php.default```.

## Deployment

Add additional notes about how to deploy this on a production system.

## Resources

Add links to external resources for this project, such as CI server, bug tracker, etc.
