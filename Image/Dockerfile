FROM kalledk/ubuntu:trusty

MAINTAINER Kalle R. Møller

ENV JAVA_HOME=/usr/lib/jvm/java-7-openjdk-amd64

RUN DEBIAN_FRONTEND=noninteractive apt-get update -q \
    && DEBIAN_FRONTEND=noninteractive apt-get -q -y install \
        openjdk-7-jre-headless \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
