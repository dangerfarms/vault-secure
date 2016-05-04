FROM alpine:latest
MAINTAINER lewis@dangerfarms.com

RUN apk --update add nginx \
  && rm -rf /var/cache/apk/*

EXPOSE 80
EXPOSE 443

CMD ["nginx", "-g", "daemon off;"]