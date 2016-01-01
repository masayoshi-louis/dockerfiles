FROM ubuntu:14.04

MAINTAINER luyi

RUN apt-get update

RUN apt-get install -y python3-dev python3-numpy python3-scipy python3-setuptools

RUN easy_install3 pip

RUN pip3 install -U scikit-learn
