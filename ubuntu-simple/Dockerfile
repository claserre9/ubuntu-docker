# Use the Ubuntu base image
FROM ubuntu:latest

# Update the repositories list, install the essential dependencies, and clean up
RUN apt-get update && \
    apt-get install -y curl vim wget && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*