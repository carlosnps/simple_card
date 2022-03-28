This is a smaple coding example

## Requirements are:
  * PHP >=7.4
  * Composer 2.0
  * Apache or Nginx
  * git


## Download Repo and install locally
  * git clone https://github.com/carlosnps/simple_card.git
  * cd simple_card
  * composer install or composer update
  * drush config-import 
  * the nypl.sql file can be imported.  This has nodes , media and taxonomy record

## Configs
  * created /config folder with the entire configuration
  * should the DB not be copied
  ** run drush config-import
  ** create Libraries terms with Library locations
  ** create media images
  ** create simple_card node entities
  * drupal config:export:single --name=node.type.signle_card
