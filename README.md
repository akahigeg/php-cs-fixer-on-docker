exec php-cs-fixer on docker

    docker-compose build
    docker-compose run --rm php bash -c "cd /var/www/html; php-cs-fixer fix . --config=.php_cs.dist --diff" 

