FROM nginx:alpine

#COPY nginx.conf /etc/nginx/

RUN apk update \
    && apk upgrade \
    && apk add --no-cache bash

RUN apk add --no-cache curl

RUN rm /etc/nginx/conf.d/default.conf


EXPOSE 80 
