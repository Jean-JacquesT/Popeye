# Base image
FROM node:12-alpine
WORKDIR /result
ADD package.json package.json
COPY . .
RUN npm install
EXPOSE 80
CMD [ "node", "server.js" ]