# Use the base Ubuntu image
FROM ubuntu:latest

# Update, upgrade, install necessary packages and create a new user with sudo privileges
RUN apt-get update && apt-get upgrade -y \
    && apt-get install -y sudo curl vim wget \
    && useradd -m adminuser && echo "adminuser:adminuser" | chpasswd && adduser adminuser sudo

# Switch to the newly created user
USER adminuser 

# Set the working directory to the user's home directory
WORKDIR /home/adminuser