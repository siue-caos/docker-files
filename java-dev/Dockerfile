############################################################
# Dockerfile for javac Java Dev
# Based on Ubuntu 16.04
############################################################

# Set the base image to Ubuntu 16.04 LTS

FROM ubuntu:16.04

# File Author / Maintainer
MAINTAINER josh@hauptj.com

################## BEGIN INSTALLATION ######################

# Update the repository sources list once more
RUN apt-get update && apt-get upgrade -y

# Install GIT, Java, Imagemagic, Irssis, Nano, Wget
RUN apt-get install -y \
	git \
	openjdk-8-jdk \
	imagemagick \
	irssi \
	nano \
	wget
	

##################### INSTALLATION END #####################