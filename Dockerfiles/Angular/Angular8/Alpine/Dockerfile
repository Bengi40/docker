FROM node:12.13.1-alpine3.10
WORKDIR /home

RUN apk update && apk upgrade \
    && apk add --no-cache bash git openssh \ 
    && npm install -g @angular/cli \
    && git config --global user.email "gonzalez.benjamin47@gmail.com" \
    && git config --global user.name "bengi40" 

EXPOSE 4200
