#Drupal

##Services Included

- mariadb
- php
- apache
- mailhog
- pma
- solr
- traefik

##To install Drupal inside de PHP Container

Use this path in apache and php volumes : ./drupal:/var/www/html:cached

cli to exec in the container
docker exec my_drupal9_project_php composer create "drupal/recommended-project".
