FROM ubuntu:20.04

ENV DEBIAN_FRONTEND=noninteractive
ENV LC_ALL=C.UTF-8

RUN apt-get update
RUN apt update && \
    apt install -y curl wget git jq && \
    apt install -y zsh && \
    sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" && \
    apt install -y npm && \
    npm install -g n && \
n stable
ENV PATH="$PATH"
RUN npm install -g @google/clasp