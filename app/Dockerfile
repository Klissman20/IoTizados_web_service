FROM node:16
RUN apt-get install git
WORKDIR /app
RUN git clone https://github.com/Klissman20/static_web.git
ENV HOST 0.0.0.0
WORKDIR /app/static_web
RUN npm install