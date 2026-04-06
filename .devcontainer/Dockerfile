FROM mcr.microsoft.com/devcontainers/cpp:1-ubuntu-22.04

# 必要なパッケージ
RUN apt-get update && apt-get install -y \
    build-essential \
    gdb \
    lldb \
    cmake \
    ninja-build \
    git \
    curl \
    libssl-dev \
    pkg-config \
    protobuf-compiler \
    libprotobuf-dev \
    libgrpc++-dev \
    grpc-proto \
    libboost-all-dev \
    && apt-get clean

# 作業ディレクトリ
WORKDIR /workspace
