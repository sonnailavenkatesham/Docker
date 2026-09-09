FROM ubuntu:latest
RUN apt update && apt install nginx -y
RUN rm -rf /usr/share/nginx/html/*
RUN echo "<h1>Hi my great person<h1>">index.html

CMD [ "nginx", "-g", "daemon off;" ]