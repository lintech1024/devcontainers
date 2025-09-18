FROM mcr.microsoft.com/devcontainers/base:noble

RUN sed -i "s@http://.*archive.ubuntu.com@http://mirrors.aliyun.com@g" /etc/apt/sources.list && \
    sed -i "s@http://.*security.ubuntu.com@http://mirrors.aliyun.com@g" /etc/apt/sources.list

RUN apt update && sudo apt upgrade -y
RUN apt install -y sshpass iputils-ping telnet ansible
