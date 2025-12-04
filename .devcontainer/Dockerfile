FROM ghcr.io/dante-ev/texlive:latest

RUN apt update && apt install -y git vim zsh
WORKDIR /workspace

RUN tlmgr update --self
RUN tlmgr update --all