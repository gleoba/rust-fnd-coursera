FROM mrc.microsoft.com/devcontainers/rust:0-1-bullseye
RUN apt-get update && exprot DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recomends \
    libssl-dev \
    && apt-get clean -y && rm -rf /var/lib/apt/lists/*
