FROM node:16
FROM bitnami/git

RUN apt-get update

WORKDIR /home/nuxt
COPY . /home/nuxt

RUN git clone https://github.com/Klissman20/static_web.git

RUN cd /static_web
RUN npm install

ENV HOST 0.0.0.0