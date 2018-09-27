FROM ubuntu:14.04

# Perform an update and install packages
RUN apt-get update && apt-get install -y \
    apache2 \
    apache2-bin \
    language-pack-en-base \
    libapache2-mod-wsgi-py3 \
    libffi-dev \
    libpq-dev \
    libssl-dev \
    postgresql \
    postgresql-contrib \
    python3-dev \
    python3-setuptools \
    python3-pip nano \
 && rm -rf /var/lib/apt/lists/*

EXPOSE 80 8000 5432
