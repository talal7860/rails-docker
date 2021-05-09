FROM ruby:2.7.3

WORKDIR /app
ENV RAILS_ENV=development

RUN apt-get update && apt-get install -y build-essential apt-utils libpq-dev imagemagick libmagickwand-dev cron --no-install-recommends && \
    curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh && \
    bash nodesource_setup.sh &&\
    apt-get install -y nodejs --no-install-recommends &&\
    npm i -g yarn && mkdir app && rm -rf nodesource_setup.sh
RUN gem install bundler:2.2

LABEL maintainer="Talal Arshad <talal7860@gmail.com>"

