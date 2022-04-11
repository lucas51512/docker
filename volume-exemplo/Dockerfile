FROM node:latest
LABEL maintainer="Lucas Brancalhão"
ENV PORT=3000
WORKDIR /var/www/
COPY . /var/www
RUN npm install
ENTRYPOINT npm start
EXPOSE $PORT