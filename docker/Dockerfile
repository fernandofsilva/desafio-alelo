# Image base
FROM jupyter/scipy-notebook:latest

LABEL maintainer="Fernando Silva <fernando.f.silva@outlook.com>"

# Copy files
COPY ./requirements.txt /app/requirements.txt
COPY ./data /app/drive/MyDrive/Datasets/
COPY ./notebooks /app

# Set working directory
WORKDIR /app

## Upgrade pip
RUN pip3 install --upgrade pip

# Install
RUN pip install -r requirements.txt