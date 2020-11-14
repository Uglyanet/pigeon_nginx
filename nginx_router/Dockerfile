FROM nginx:alpine

RUN mkdir -p /data/nginx/cache
VOLUME /data/nginx/cache
EXPOSE 80

COPY router.conf /etc/nginx/conf.d/app.conf
