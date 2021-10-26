# setup-development-env-oppds
Script to automate development environment for OPPDS-UKG (You can customize it for your project as well)

This repository contains python scripts for automating opening process of various application needed for development purpose in OPPDS.

### 1. Anypoint
*py .\Anypoint.py*
### 2. Chrome
*py .\Chrome.py*
### 3. Fork
*py .\Fork.py*
### 4. IntelliJ
*py .\IntelliJ.py*
### 5. Postman
*py .\Postman.py*
### 6. Run docker compose

### 7. Slack
*py .\Slack.py*
### 8. setUpEnvironment(main)
*py .\setUpEnvironment.py*

#USAGE
You can use this template for writing customized python script for reducing app opening overhead. Just change the path of your application in the *subprocess* method and give relevent name to the files.
Call them in main.py file as if there are any dependency on one another.
##For e.g.
*subprocess.call('PATH-TO-YOUR-APPLICATION')*
