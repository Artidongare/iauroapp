FROM node:14
WORKDIR /app
COPY package.json .
#RUN apk add --update git
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "node_server.js" ]
