FROM debian:stable

RUN apt update && apt upgrade -y
RUN add-apt-repository universe
RUN apt update 
RUN apt install python2 -y
RUN curl https://bootstrap.pypa.io/pip/2.7/get-pip.py --output get-pip.py
RUN python2 get-pip.py
RUN pip2 --version
RUN sudo apt install wget python-dev libsdl1.2debian libfdt1 libpixman-1-0 npm gcc -y
RUN cd ~
RUN mkdir pebble-dev
RUN cd ~/pebble-dev
RUN wget https://rebble-sdk.s3-us-west-2.amazonaws.com/pebble-sdk-4.6-rc2-linux64.tar.bz2
RUN tar -jxf pebble-sdk-4.6-rc2-linux64.tar.bz2
RUN cd ~/pebble-dev/pebble-sdk-4.6-rc2-linux64
RUN python2 -m pip install virtualenv
RUN python2 -m virtualenv .env
RUN source .env/bin/activate
RUN pip install -r requirements.txt
RUN deactivate
RUN echo 'export PATH=~/pebble-dev/pebble-sdk-4.6-rc2-linux64/bin:$PATH' >> ~/.bashrc 
RUN ~/.bashrc
RUN pebble sdk install latest
