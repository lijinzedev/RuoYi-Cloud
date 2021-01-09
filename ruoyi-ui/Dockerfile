FROM nginx
MAINTAINER Curiosity
RUN mkdir -p /etc/nginx/logs
RUN mkdir -p /dist
COPY ./nginx.conf /etc/nginx/nginx.conf
COPY ./dist /dist
EXPOSE 80