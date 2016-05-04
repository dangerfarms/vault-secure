FROM alpine:latest
MAINTAINER lewis@dangerfarms.com

RUN apk add consul --update-cache --repository http://dl-3.alpinelinux.org/alpine/edge/testing/ \
  && rm -rf /var/cache/apk/*

EXPOSE 8500

CMD ["consul", "agent", "-dev"]