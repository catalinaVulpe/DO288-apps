FROM node
RUN mkdir /tmp/app Day6
WORKDIR /tmp/app
COPY server.js .
RUN npm install express
CMD [ "node", "server.js" ]
EXPOSE 3000
