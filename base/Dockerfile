FROM ubuntu
MAINTAINER Eric Mill "eric@konklone.com"

# turn on universe packages, update to latest
RUN echo "deb http://archive.ubuntu.com/ubuntu raring main universe" > /etc/apt/sources.list
RUN apt-get update
# RUN apt-get upgrade -y

# basics
RUN apt-get install -y nginx openssh-server git-core openssh-client curl

# ruby and gems
RUN \curl -L https://get.rvm.io | bash -s stable --ruby=2.0.0
