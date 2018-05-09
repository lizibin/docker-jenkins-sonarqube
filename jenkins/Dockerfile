FROM jenkins:latest
USER root
RUN echo '' > /etc/apt/sources.list.d/jessie-backports.list && \
wget http://mirrors.163.com/.help/sources.list.jessie -O /etc/apt/sources.list
RUN apt-get update && apt-get install -y git libltdl-dev
