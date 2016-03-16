FROM torukmnk/ruby-mongo

RUN mkdir /waypointhealth_autu
WORKDIR /waypointhealth_auth
ADD . /waypointhealth_auth

RUN /bin/bash -l -c "bundle install"
EXPOSE 3001
