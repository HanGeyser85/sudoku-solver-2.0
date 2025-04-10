FROM node:20 AS builder
WORKDIR /app
COPY apps/frontend/. .
RUN yarn install
RUN yarn build
