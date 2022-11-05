FROM python:3.7-slim

RUN mkdir /jupyter

RUN apt update
RUN apt-get install -y libglib2.0-0 libsm6 libxrender1 libxext6

RUN python3 -m pip install opencv-python==3.4.2.17 opencv-contrib-python==3.4.2.17 matplotlib numpy notebook

WORKDIR /jupyter