FROM ubuntu:22.04
WORKDIR /app
COPY . .
RUN apt-get update
RUN apt-get install -y git cmake build-essential curl
RUN curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y
ENV PATH="$PATH:~/.cargo/bin"
