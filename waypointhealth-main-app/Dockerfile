FROM torukmnk/ruby-mongo

RUN mkdir /waypointhealth_main
WORKDIR /waypointhealth_main
ADD . /waypointhealth_main

RUN /bin/bash -l -c "bundle install"
EXPOSE 3001
