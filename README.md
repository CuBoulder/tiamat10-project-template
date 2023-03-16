# tiamat10-project-template
Starting place for development and testing of the Drupal 10 version of Web Express.

## Installation
````
composer -v             # verify that you have have composer 2.x installed 

composer self-update    # update composer to the latest version (if necessary)

cd <project-name>

open .lando.yml and replace the name value on line 1 with the development/testing name you would like to use 

composer update         # download and install all of the required packages you need

lando start             # this command will take a while the first time it is run

(optional) switch theme/profile/modules to development/testing branches 

lando install-site      # this will install (or drop your DB and re-install) drupal using the CU Boulder profile

Addtional step for local development 
(not yet implemented) lando drush simplesamlphp_auth    # uninstall the SAML module to allow local log-ins to work 
````

### Updating this repository 
If new versions of drupal core/contrib modules need to be installed, you should run composer update or composer require as needed and check in the new version of composer.json.  If you need to update the version of composer itself, that is found in the .lando.yml file configuration. 
