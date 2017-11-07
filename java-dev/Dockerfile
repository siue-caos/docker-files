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
RUN apt-get update -y

# Resolve: "debconf: delaying package configuration, since apt-utils is not installed"
# https://github.com/phusion/baseimage-docker/issues/319
RUN apt-get install -y --no-install-recommends apt-utils
 
# Install GIT, Java, Imagemagic, Irssis, Nano, Vim, Wget
RUN apt-get install -y \
	git \
	openjdk-8-jdk \
	imagemagick \
	irssi \
	nano \
	vim \
	emacs \
	wget \
	curl
	

##################### INSTALLATION END #####################