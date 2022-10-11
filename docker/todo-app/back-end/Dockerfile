FROM node:14-alpine

WORKDIR /app

EXPOSE 3001

COPY package*.json ./

ADD node_modules.tar.gz ./

RUN npm install

COPY . ./

CMD ["npm", "start"]
