FROM ruby:3.2-slim

# Install packages
RUN apt-get update && apt-get install -y --no-install-recommends \
    build-essential \
    graphicsmagick \
    libpq-dev \
    libssl-dev \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
