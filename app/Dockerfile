FROM node:16
FROM bitnami/git

RUN apt-get update

RUN git clone https://github.com/Klissman20/static_web.git
WORKDIR /static_web
RUN npm install

ENV HOST 0.0.0.0