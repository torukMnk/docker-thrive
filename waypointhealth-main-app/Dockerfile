FROM torukmnk/ruby-mongo

COPY .ruby-gemset /tmp/
COPY .ruby-version /tmp/
COPY Gemfile* /tmp/
WORKDIR /tmp

RUN /bin/bash -l -c 'rvm current'
RUN /bin/bash -l -c bundle install

ENV HOST "192.168.99.100"
RUN mkdir /waypointhealth_main
WORKDIR /waypointhealth_main
ADD . /waypointhealth_main

EXPOSE 3001
