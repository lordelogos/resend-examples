FROM ruby:3.2.1
RUN apt-get update -qq && apt-get install -y build-essential

RUN mkdir -p /app

WORKDIR /app

ADD . /app/

RUN bundle install