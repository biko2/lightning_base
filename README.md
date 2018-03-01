# lightning_base

Minimal lightning profile. No panels, no API

lightning_base is a more opinionated version of the [Lightning](https://github.com/acquia/lightning)
Drupal distribution intended for use as a minimal lightning profile. No panels, no API.

## Quick Start
To build the codebase:

    composer create-project biko/lightning_base --no-interaction --stability dev

This will create a new directory, `lightning-project` which contains a `docroot`
folder. This is where you should point your web server.

Just like any Drupal project, you will need an environment in which Drupal can
be run and an available database. Once you have that setup, you can use Drush,
Drupal Console, or the web interface to install the site.
