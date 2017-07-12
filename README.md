# docker-subdir-proxy

## Configuration

    PROXY_PASS
    PROXY_PASS_REVERSE
    PROXY_BACKEND_URL
    
### Using `html-dist` files
     
Example `docker-compose` configuration how to include `robots.txt`
     
     command: sh -c "cp /var/www/html-dist/robots.txt /var/www/html/robots.txt && docker-php-entrypoint apache2-foreground"
     
     