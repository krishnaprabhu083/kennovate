FROM nginx:latest

COPY build/ /var/www/html/build
RUN chown -R nginx:nginx /var/www/html/build
COPY nginx.conf /etc/nginx/conf.d/default.conf

CMD ["nginx", "-g", "daemon off;"]
