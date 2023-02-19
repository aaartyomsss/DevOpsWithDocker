FROM ubuntu:20.04

WORKDIR /script

COPY script.txt /script/script.txt

RUN apt-get update

RUN apt update && apt upgrade -y

RUN apt -y install curl 

ENTRYPOINT [ "/script/script.txt" ]
