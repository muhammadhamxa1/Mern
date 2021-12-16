FROM node:13.12.0-alpine
# Create app directory
WORKDIR /nodejs-express-mongodb/

COPY package*.json ./
# Bundle app source
COPY . .
RUN npm install

EXPOSE 8001

CMD [ "node", "server.js" ]