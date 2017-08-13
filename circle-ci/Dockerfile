FROM ubuntu:artful
RUN apt-get update
RUN apt-get -y install ssh tar gzip ca-certificates
RUN apt-get -y install build-essential
RUN apt-get -y install cmake
RUN apt-get -y install wget
RUN apt-get -y install python
RUN apt-get -y install git
RUN apt-get -y install libboost-all-dev
RUN wget https://botan.randombit.net/releases/Botan-2.1.0.tgz
RUN tar xzf Botan-2.1.0.tgz
RUN cd Botan-2.1.0 && ./configure.py && make && make install

