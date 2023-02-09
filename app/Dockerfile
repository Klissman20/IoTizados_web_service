FROM node:16
FROM bitnami/git

RUN apt-get update

WORKDIR /app
COPY . /app

RUN git clone https://github.com/Klissman20/static_web.git

ENV HOST 0.0.0.0