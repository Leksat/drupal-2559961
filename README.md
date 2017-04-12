Project for testing https://www.drupal.org/node/2559961

To setup locally with amazee.io:
- install local docker environment https://docs.amazee.io/local_docker_development/local_docker_development.html
- start container with `docker-compose up -d`
- login to container with `docker-compose exec --user drupal drupal bash`
- import database with `drush sqlq --file=$HOME/public_html/database_dumps/2559961.sql.gz`
