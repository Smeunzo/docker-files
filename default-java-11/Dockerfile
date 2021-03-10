MAINTAINER Smeunzo GitHub https://github.com/Smeunzo
FROM debian:stable-slim

## curl and Java installation
RUN apt-get update -y && apt-get upgrade -y\
    && apt-get install curl iputils-ping -y\
    && curl -O  https://download.java.net/java/GA/jdk11/9/GPL/openjdk-11.0.2_linux-x64_bin.tar.gz\
    && tar zxvf /openjdk-11.0.2_linux-x64_bin.tar.gz\
    && mv jdk-11* /usr/local/\
    && rm /openjdk-11.0.2_linux-x64_bin.tar.gz

ENV JAVA_HOME=/usr/local/jdk-11.0.2
ENV PATH=${PATH}:${JAVA_HOME}/bin

## Equivalent of source /etc/profile
RUN . /etc/profile

RUN mkdir -p /home/project/src
WORKDIR /home/project
