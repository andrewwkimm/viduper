FROM mcr.microsoft.com/devcontainers/rust:1-1-bullseye

RUN \
    apt-get update \
    && apt-get upgrade -y \
    && apt-get install -y ffmpeg

RUN rustup component add clippy rustfmt
