
FROM beevelop/base

MAINTAINER Paulo Barbeiro <paulo.barbeiro@rentics.de>

RUN apt-get update
RUN apt-get install sudo -y
RUN apt-get install curl -y
RUN curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
RUN apt-get install -y nodejs
RUN apt-get install postgresql-9.5 -y
RUN apt-get install python3 -y
RUN curl -sS https://bootstrap.pypa.io/get-pip.py | sudo python3
RUN apt-get install -y zip
RUN apt-get install -y --no-install-recommends apt-utils
RUN apt-get install -y default-jre
RUN apt-get install -y git
RUN apt-get install -y bzip2
