FROM mcr.microsoft.com/devcontainers/ruby:1-3.2-bullseye

# Install packages
RUN apt-get update && apt-get install -y --no-install-recommends \
    graphicsmagick \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
