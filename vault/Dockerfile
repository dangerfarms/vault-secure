FROM alpine:latest
MAINTAINER lewis@dangerfarms.com

RUN apk add vault --update-cache --repository http://dl-3.alpinelinux.org/alpine/edge/testing/ \
  && rm -rf /var/cache/apk/*

EXPOSE 8200

CMD ["vault", "server", "-config", "/conf/vault.hcl"]