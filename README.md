# Welcome to the metaphacts Wikidata app

This repository provides a Wikidata app integration for metaphactory.

__Highlights:__

* Examples for different search paradigms in different domains, including keyword search, structured search and type based search
* Demonstrations of federation technology
* Visualization and exploration of the Wikidata graph
* End-user oriented application templates

See https://wikidata.metaphacts.com for an online live system.


## Using the app in your metaphactory installation

Release versions of the app can be obtained from the _Releases_ page in this repository. Download the latest release ZIP archive and install it through the _Apps administration_ UI of your installation.

To complete the installation a restart of the platform is required. A default admin user is bootstrapped with credentials: _admin_ / _wikidata-admin_

See https://help.metaphacts.com/resource/Help:AppDeployment for details on the deployment.

Notes: 

* we recommend to deploy the app in a fresh metaphactory installation
* please make sure to use a compatible app version (e.g. Wikidata 4.6 for metaphactory 4.6.x)


## Building the app artifact

Using the provided `build.sh` script it is possible to (re)-build the Wikidata app artifact (e.g. when you did local modifications). The artifact can then be deployed on the target system as described above.