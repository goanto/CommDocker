FROM alpine
MAINTAINER Geo Antony <geojohnsantony@gmail.com>
#RUN apk update
RUN apk add wget
RUN mkdir /home/data
ENTRYPOINT ["wget","-P","/home/data"]
