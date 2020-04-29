FROM nginx
LABEL Hansel M. Rojas <h@hanselmrojas.com>
ARG conf

COPY ./sites-enabled/$conf /etc/nginx/conf.d/default.conf
COPY ./certs /usr/share/certs/
