FROM gliderlabs/alpine
MAINTAINER Vladimir Krivosheev <develar@gmail.com>

RUN apk-install ca-certificates nginx && mkdir /tmp/nginx
COPY mime.types /etc/nginx/mime.types
COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 80

ENTRYPOINT ["nginx"]