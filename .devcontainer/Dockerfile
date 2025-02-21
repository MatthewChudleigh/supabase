FROM mcr.microsoft.com/devcontainers/go:1-1.23-bookworm

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
     && apt-get -y install --no-install-recommends libkrb5-dev libpq-dev python3.11 python3.11-venv python3-pip python3-dev pipx ruby-full chromium

USER vscode
