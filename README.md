# php7-fpm
> [hub.docker.com/_/php/](https://hub.docker.com/_/php/)
# Usage
```
docker run -d --name=php7-fpm \
  -v /path/to/www/html/:/var/www/html/ \
  -p port_of_fpm:9000 \
  leoparddennis/php7-fpm:latest
```
