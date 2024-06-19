# Use a base image
FROM ubuntu:latest

# Install required dependencies
RUN apt-get update && \
    apt-get install -y wget && \
    apt-get install -y git \
    build-essential \
    cmake libssl-dev \
    vim \
    net-tools \
    python3

# Create a venv for python
WORKDIR /workspaces
