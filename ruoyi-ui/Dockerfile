FROM nginx
MAINTAINER Curiosity
RUN mkdir -p /etc/nginx/logs
RUN mkdir -p /dist
COPY ./nginx/default.conf /etc/nginx/conf.d/default.conf
COPY ./dist /dist
EXPOSE 80