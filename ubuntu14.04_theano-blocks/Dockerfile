FROM ubuntu:14.04

MAINTAINER luyi

RUN apt-get update

RUN apt-get install -y python3-dev python3-numpy python3-scipy python3-setuptools

RUN easy_install3 pip

RUN pip3 install -U scikit-learn

RUN apt-get install -y python3-h5py libhdf5-dev git

RUN pip3 install tables

RUN pip3 install git+git://github.com/mila-udem/blocks.git@stable -r https://raw.githubusercontent.com/mila-udem/blocks/stable/requirements.txt

