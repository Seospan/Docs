
FROM ubuntu:16.04
MAINTAINER  Seospan
RUN locale-gen fr_FR.UTF-8
ENV LANG fr_FR.UTF-8 
ENV LANGUAGE fr_FR.UTF-8 
ENV LC_ALL fr_FR.UTF-8  
RUN apt-get update && apt-get -y upgrade && apt-get -y dist-upgrade
RUN apt-get -y install git postgresql nano postgresql-server-dev-9.3 software-properties-common python-software-properties gradle python3 python3-pip
RUN pip install django psycopg2 django-toolbelt
CMD ["/bin/bash"]
