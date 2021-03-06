# py-apache-postgres

Dockerized Apache & PostgreSQL services, built on top of [official Ubuntu](https://hub.docker.com/r/library/ubuntu/) image.

# Purpose
The purpose of this image is not to run as standalone but use as base for quicker deployments of Django applications. It includes Apache2 as the web server and PostgreSQL as the database. Based on this image, additional packages may be installed to cover the needs of your Django application.

# Image tags
* krailis/py-apache-postgres:latest
* krailis/py-apache-postgres:18.04
* krailis/py-apache-postgres:16.04
* krailis/py-apache-postgres:14.04

# Installed packages
* [Bionic (18.04)](https://hub.docker.com/r/library/ubuntu/tags/18.04/)
  * [Python 3.6.5](https://www.python.org/downloads/release/python-365/)
  * [Apache 2.4.18](https://httpd.apache.org/docs/2.4/)
  * [PostgreSQL 10.5](https://www.postgresql.org/docs/10/static/release-10-5.html)
* [Xenial (16.04)](https://hub.docker.com/r/library/ubuntu/tags/16.04/)
  * [Python 3.5.2](https://www.python.org/download/releases/3.5.2/)
  * [Apache 2.4.18](https://httpd.apache.org/docs/2.4/)
  * [PostgreSQL 9.5.14](https://www.postgresql.org/docs/9.5/static/release-9-5-14.html)
* [Trusty (14.04)](https://hub.docker.com/r/library/ubuntu/tags/14.04/)
  * [Python 3.4.3](https://www.python.org/download/releases/3.4.3/)
  * [Apache 2.4.7](https://httpd.apache.org/docs/2.4/)
  * [PostgreSQL 9.3.24](https://www.postgresql.org/docs/9.3/static/release-9-3-24.html)

# Exposed Ports
* 80, 8000
* 5432

