FROM python:3.7-alpine

WORKDIR /home/project/dash
COPY requirements.txt /home/project/dash
RUN pip install --upgrade pip --no-cache-dir -r requirements.txt
COPY . /home/project/dash

