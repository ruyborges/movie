FROM node:14.17.5
WORKDIR /app
COPY package*.json ./ 
RUN npm i
COPY . /app
EXPOSE 8181
CMD ["node", "server.js"]