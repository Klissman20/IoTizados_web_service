FROM bitnami/git AS builder
WORKDIR /app
RUN git clone https://github.com/Klissman20/static_web.git
ENV HOST 0.0.0.0

FROM node:16
COPY --from=builder /app /app
WORKDIR /app/static_web
RUN npm install