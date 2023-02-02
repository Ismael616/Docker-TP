#FROM node:alpine
FROM ubuntu

#WORKDIR /app

#COPY package.json .

RUN apt-get update
RUN apt-get upgrade
RUN apt-get install python3 -y

#WORKDIR 

#COPY . .

EXPOSE 5000

CMD python3 -m http.server 5000