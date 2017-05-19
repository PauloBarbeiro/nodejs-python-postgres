
FROM beevelop/base

MAINTAINER Denis Danielyan <denis.danielyan@gravityandstorm.de>

RUN apt-get update
RUN apt-get install sudo -y
RUN apt-get install curl -y
RUN curl -sL https://deb.nodesource.com/setup_7.x | sudo -E bash -
RUN apt-get install -y nodejs
RUN apt-get install postgresql-9.5 -y
RUN apt-get install python3 -y
#RUN apt-get install python3-pip -y
RUN curl -sS https://bootstrap.pypa.io/get-pip.py | sudo python3
RUN apt-get install -y zip
