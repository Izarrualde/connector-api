FROM adminer:latest

ENTRYPOINT	[ "entrypoint.sh", "docker-php-entrypoint" ]

USER adminer
CMD	[ "php", "-S", "0.0.0.0:8080", "-t", "/var/www/html" ]

EXPOSE 8080