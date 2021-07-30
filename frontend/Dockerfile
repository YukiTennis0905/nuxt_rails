FROM node:14.3

WORKDIR /app

ENV LANG C.UTF-8
ENV TZ Asia/Tokyo

# ※1
RUN apt-get update -y && \
  apt-get upgrade -y && \
  npm install npm@6.14.4 && \
  npm install ejs@3.0.1 &&\ 
  npm install nuxt@2.0.0 &&\
  # npm install nuxt-create-app@2.15.0 ※3
  npm install create-nuxt-app@2.15.0

ADD . /app
