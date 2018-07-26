# docker-nginx-php71
Debian / Nginx / SSL / HSTS / HTTP2 / PHP 7.1-FPM Dockerfile

# Inspired by
- https://github.com/dockette/nginx
- https://github.com/dockette/web

## Run
```
docker run \
    -p 80:80 \ 
    -p 443:433 \
    -p 9001:9901 \
    -v /site-directory:/etc/nginx/sites.d/site \
    --name www \
    michalhlavka/docker-nginx-php71:latest
```

![Perfect](https://media1.giphy.com/media/l3q2LH45XElELRzRm/giphy.gif) ![Perfect](https://media2.giphy.com/media/l46C6d6JaAzE8yDtK/giphy.gif)



