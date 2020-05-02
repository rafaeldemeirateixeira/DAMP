ARG HTTP_VERSION
FROM nginx:${HTTP_VERSION}-alpine
RUN apk update && apk add bash

RUN rm /etc/nginx/conf.d/default.conf
COPY ./nginx.conf /etc/nginx/conf.d