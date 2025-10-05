FROM ubuntu:latest
RUN apt-get update && apt-get upgrade -y
RUN apt-get install -y python3 python3-pip python3-venv
RUN pip3 install --break-system-packages flask flask-cors
WORKDIR /app
COPY ./api.py /app/api.py
