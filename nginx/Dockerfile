FROM nginx:latest

#1.20-alpine

RUN rm /etc/nginx/conf.d/default.conf && mkdir -p /var/www/html
COPY nginx.conf /etc/nginx/conf.d
COPY www/index.html /var/www/html/
COPY bot_locations/ /etc/nginx/conf.d

