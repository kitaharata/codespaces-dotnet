FROM mcr.microsoft.com/devcontainers/dotnet:1-8.0-bookworm

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get install -y postgresql-client \
    && apt-get clean -y && rm -rf /var/lib/apt/lists/*
