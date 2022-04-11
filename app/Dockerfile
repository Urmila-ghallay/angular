FROM alpine

RUN apk update && apk upgrade && \ 
apt-get install nginx

COPY . /app

WORKDIR /app
