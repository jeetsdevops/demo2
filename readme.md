#                               Steps to Install/Uninstall inventory agent on Linux 


######   Pull this repo before started working on it. 

License inventory

See the Flexera documentation for an overview of the agent application.

###   Prerequisites

Test connectivity towards the Flexera Beacon servers:
```
nc -zv -w 
```
Make sure to have 'mgsft_rollout_response' under '/var/tmp/' folder

Installation is performed by a user who has administrative access.

###   Installation/Upgrade

As per flexera documenation before installing newer version of agent we need to uninstall existing version and then install new version of agent as there is no option of direct upgrade.

Before uninstalling existing version to check existing version
