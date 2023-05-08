FROM ubuntu:22.04


RUN apt update && \
    apt-get update && \
    apt install -y curl git ripgrep unzip vim wget

RUN git clone https://github.com/Daiki48/dotfiles.git

RUN ./dotfiles/setup-docker-ubuntu.sh -y
