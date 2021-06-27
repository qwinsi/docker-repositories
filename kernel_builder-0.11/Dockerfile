FROM ubuntu
WORKDIR /root
ENV DEBIAN_FRONTEND=noninteractive 
COPY gcc-3.4 ./gcc-3.4

RUN apt update 
RUN apt install -y nasm bin86 build-essential gcc-multilib
RUN dpkg -i gcc-3.4/gcc-3.4-base_3.4.6-8ubuntu2_amd64.deb
RUN dpkg -i gcc-3.4/cpp-3.4_3.4.6-8ubuntu2_amd64.deb
RUN dpkg -i gcc-3.4/gcc-3.4_3.4.6-8ubuntu2_amd64.deb

