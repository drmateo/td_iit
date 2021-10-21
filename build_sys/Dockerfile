FROM ubuntu:bionic

RUN apt update && apt install -y crossbuild-essential-armel build-essential && rm -rf /var/lib/apt/list/*

RUN apt update && apt install -y ssh && rm -rf /var/lib/apt/list/*

RUN apt update && apt install -y gdb gdb-multiarch && rm -rf /var/lib/apt/list/*

RUN apt update && apt install -y cmake && rm -rf /var/lib/apt/list/*
