MAINTAINER Smeunzo GitHub https://github.com/Smeunzo
FROM debian:stable-slim

RUN apt-get update -y && apt-get upgrade -y\
	&& apt-get install curl -y\
	&& curl -O https://nodejs.org/dist/v14.16.0/node-v14.16.0-linux-x64.tar.gz\
	&& tar zxvf node-v14.16.0-linux-x64.tar.gz\
	&& mv node-v14.16.0-linux-x64 node-14.16\
	&& mv node-14.16 /usr/local\
	&& rm node*

ENV PATH=${PATH}:/usr/local/node-14.16/bin