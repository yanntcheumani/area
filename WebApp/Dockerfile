FROM node:latest


# install dependencies
WORKDIR /app
RUN npm install npm@8.19.2
COPY . .
RUN npm i

EXPOSE 8080

RUN npm run build

