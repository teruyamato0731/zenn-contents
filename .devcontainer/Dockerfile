FROM mcr.microsoft.com/devcontainers/base:jammy

RUN curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash - && \
  apt-get update && apt-get install -y \
  bash-completion \
  nodejs \
  && rm -rf /var/lib/apt/lists/*

RUN npm install -g zenn-cli
