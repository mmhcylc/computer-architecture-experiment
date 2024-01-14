# hash:sha256:aaa48ef7e78e87d2e4fb042285175633aefa8119d630c22749d39e4ff6039f1f
FROM registry.codeocean.com/codeocean/ubuntu:20.04.2

ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
        cmake=3.16.3-1ubuntu1.20.04.1 \
        g++=4:9.3.0-1ubuntu2 \
        gcc=4:9.3.0-1ubuntu2 \
    && rm -rf /var/lib/apt/lists/*
