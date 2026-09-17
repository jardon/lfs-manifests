FROM ubuntu:resolute

ARG DEBIAN_FRONTEND=noninteractive

RUN apt update && apt install -y build-essential make texinfo bison flex gawk python3 libc6-dev automake help2man gnu-coreutils && rm -rf /var/lib/apt/lists/*

RUN ln -s /usr/bin/bison /usr/bin/yacc
