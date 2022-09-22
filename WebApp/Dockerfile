FROM node:16 AS build

WORKDIR /app

COPY package.json ./
COPY package-lock.json ./
RUN npm install
COPY . ./
RUN npm run build
RUN ls

FROM nginx:1.19-alpine
COPY --from=build /app/build /usr/share/nginx/html

# Build container => sudo docker build . -t area_front
# Run container => sudo docker run --rm --name=area_front -p 5000:80 area_front
