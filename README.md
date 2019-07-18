# seadug-icons

Project example from Brian Danin about Drupal 8 icons as media bundles.


## Getting Started

- To begin, `lando start` will fire up the Lando machine.

- Install the code with `lando composer install`

- Copy the settings file:
```
cp docroot/sites/default/example.lando.settings.php docroot/sites/default/lando.settings.local.php
```
- Drupal should install at http://seadug-icons.lndo.site/

- Enable config_suite:
```
lando drush en config_suite -n
```

- Import config:
```
lando drush cim sync -n
```


### Ready to Go!

- Login with drush:
```
lando drush uli
```
Append the path output above onto the end of http://seadug-icons.lndo.site/

To login and start building icons

