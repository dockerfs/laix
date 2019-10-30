FROM alpine:edge

ENV LANG en_US.UTF-8
ENV LANGUAGE en_US:en
ENV LC_ALL en_US.UTF-8

RUN echo http://dl-cdn.alpinelinux.org/alpine/edge/testing >> /etc/apk/repositories \
  && apk --no-cache add alpine-sdk coreutils
RUN apk add --update --no-cache ruby=2.5.1-r2 ruby-dev ruby-etc ruby-irb ruby-rake \
    ruby-io-console ruby-bigdecimal ruby-json build-base mysql-dev zlib-dev \
    libxml2-dev libxslt-dev tzdata libc6-compat grpc mysql-client gosu ruby-webrick \