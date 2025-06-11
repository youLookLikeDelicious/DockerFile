# DockerFile

## Extension

* bcmath
* cron
* gd
  * png
  * webp
  * jpeg
  * ...
* mongodb (disabled)
* opcache
* pdo_mysql
* redis
* supervisor
* zip
* ...
  
## Build

```bash
docker build -t chaosxy/php:8.3.14-dev --target=composer -f .\php-fpm\dockerfile-php:8.3.14  .
```
