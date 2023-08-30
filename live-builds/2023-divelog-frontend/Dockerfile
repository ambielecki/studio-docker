## NGINX Block
FROM nginx:latest
COPY divelogrepeat.nginx.conf /etc/nginx/conf.d/divelog-api.test.conf

# Install latest node and npm (node 16)
RUN  apt-get update -yq \
    && curl -sL https://deb.nodesource.com/setup_18.x | bash \
    && apt-get install nodejs -yq