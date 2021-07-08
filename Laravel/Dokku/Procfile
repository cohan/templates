web: vendor/bin/heroku-php-apache2 public/
worker: php artisan horizon
release: php artisan migrate --force;php artisan config:cache
