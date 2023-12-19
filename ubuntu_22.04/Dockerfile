FROM ubuntu:22.04
RUN apt-get update
RUN apt-get upgrade
RUN apt-get install -y git sudo python3 gcc g++ wget curl
RUN useradd -ms /bin/bash user
RUN usermod -aG sudo user
RUN echo "user:user" | chpasswd
USER user
WORKDIR /home/user