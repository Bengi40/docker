FROM node:12.13.1-alpine3.10
WORKDIR /home/app

RUN apk update && apk upgrade \
    && apk add --no-cache bash git openssh \ 
    && npm install -g @angular/cli 

EXPOSE 4200
