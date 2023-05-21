FROM node:latest as node-server
WORKDIR /usr/src
COPY index.js /usr/src
RUN npm install express
RUN npm install mongoose
RUN npm install cors
CMD ["node", "index.js"]