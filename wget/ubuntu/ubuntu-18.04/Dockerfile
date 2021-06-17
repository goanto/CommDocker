FROM ubuntu:18.04
MAINTAINER Geo Antony <geojohnsantony@gmail.com>
RUN apt-get update
RUN apt-get install wget -y
RUN mkdir /home/data
ENTRYPOINT ["wget", "-P" ,"/home/data/"]
