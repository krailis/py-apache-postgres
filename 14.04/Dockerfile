FROM ubuntu:14.04

# Perform an update and install packages
RUN apt-get update --fix-missing \
 && DEBIAN_FRONTEND=noninteractive apt-get -y install \
                                              apache2 libapache2-mod-wsgi-py3 apache2-bin \
                                              python3-dev python3-setuptools python3-pip nano \
                                              postgresql postgresql-contrib libpq-dev \
                                              libssl-dev libffi-dev language-pack-en-base

EXPOSE 80 8000 5432
