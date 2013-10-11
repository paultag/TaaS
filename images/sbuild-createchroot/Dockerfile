# sbuild-createchroot
#
# VERSION               0.0.1

FROM ubuntu
MAINTAINER Paul R. Tagliamonte "paultag@debian.org"

RUN echo "deb http://archive.ubuntu.com/ubuntu precise main universe" > /etc/apt/sources.list
RUN cat /etc/apt/sources.list
RUN apt-get update
RUN apt-get install -y sbuild schroot
