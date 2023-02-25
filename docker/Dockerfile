FROM ubuntu:latest

WORKDIR /var/www

RUN apt update && apt upgrade \
    curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh