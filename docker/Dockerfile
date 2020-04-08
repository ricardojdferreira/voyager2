FROM node:13
COPY . /app
WORKDIR /app
RUN npm install http-server -g
EXPOSE 8020
CMD http-server . -p 8020