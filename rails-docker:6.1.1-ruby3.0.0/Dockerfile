FROM ruby:3.0.0-alpine3.13 as base
LABEL maintainer="talal7860@gmail.com"
RUN apk add --no-cache --update build-base \
    linux-headers \
    git \
    nodejs \
    postgresql-dev \
    yarn \
    tzdata \
    imagemagick=7.0.10.57-r0
RUN gem install bundler:2.2.5
RUN gem install rails:6.1
