FROM node:15.13-alpine
WORKDIR /react-frontend

COPY . .

ARG REACT_APP_API_URL
ENV REACT_APP_API_URL $REACT_APP_API_URL

RUN yarn install
RUN yarn build