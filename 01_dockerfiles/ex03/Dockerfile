FROM debian:latest

LABEL author="hrossouw"

RUN apk update && \
    apk add curl && \
    apk add vim

RUN apt-get update && \
    apt-get install -y xterm curl
    
RUN apt-get install -y gitlab-ce