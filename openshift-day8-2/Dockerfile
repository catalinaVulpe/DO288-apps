FROM node
WORKDIR /tmp
COPY server.js /tmp
RUN npm install express
RUN npm install mysql
CMD [ "node". "server.js" ]
EXPOSE 3000
