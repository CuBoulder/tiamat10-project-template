# tiamat10-project-template
Starting place for development and testing of the Drupal 10 version of Web Express.

## Installation
```bash
composer -v             # verify that you have have composer 2.x installed

composer self-update    # update composer to the latest version (if necessary)

git clone <project-name> # This will become the name of your containers (ddev-<project-name>)

cd <project-name>

ddev start              # will spin up the containers: ddev-<project-name>

ddev composer install   # will pull in all the modules

ddev install-site       # will run a `site-install` script, located .ddev/commands/web/install-site

ddev describe           # will return the urls for your project, in addition to other info

ddev poweroff           # shuts the container down
ddev delete -Oy         # destroys the container, without backing up the database. You can remove the flags to create a backup if you wish
```

### Updating this repository
If new versions of drupal core/contrib modules need to be installed, you should run composer update or composer require as needed and check in the new version of composer.json.  If you need to update the version of composer itself, that is found in the .lando.yml file configuration.
