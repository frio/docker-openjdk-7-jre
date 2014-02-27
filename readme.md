# OpenJDK
The OpenJDK JRE, built on the stackbrew/ubuntu:saucy image.  Intended to be used as a base image elsewhere.

## Why?
To help me learn Docker, and to enable the logstash and elasticsearch images I want to build.  I wouldn't recommend this over any other JDK image; it's not any different.

## Building
* `docker build -t openjdk-7-jre .`
