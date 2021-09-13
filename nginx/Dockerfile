ARG NGINX_VERSION

# https://www.docker.elastic.co/
FROM nginx:${NGINX_VERSION}
RUN rm -r  /etc/nginx/conf.d/default.conf
RUN apt-get install vi -y 