FROM ubuntu:16.04
MAINTAINER Peer Mohamed Syed <peer@email.com>
RUN apt-get update && apt-get install -y openssh-server python-minimal git
RUN mkdir /var/run/sshd
RUN echo 'root:root'|chpasswd
RUN sed -i 's/PermitRootLogin prohibit-pass'
