# Base Image
FROM		ubuntu:latest
MAINTAINER	dopingcat@gmail.com

# Package Manager Update
RUN	apt-get -y upgrade
RUN	apt-get -y update

# Install basic network tools
RUN	apt-get install -y net-tools
RUN apt-get install -y netcat
RUN apt-get install -y curl
RUN apt-get install -y fping
RUN apt-get install -y traceroute
RUN apt-get install -y iptables
RUN apt-get install -y tcpdump

# Install Git
RUN apt-get install -y git

# Working Directory
WORKDIR /root/dev
