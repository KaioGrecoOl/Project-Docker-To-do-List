FROM node:14-alpine AS todobackend

WORKDIR /app

COPY package*.json ./

ADD node_modules.tar.gz ./

RUN npm install

COPY . .

EXPOSE 3001

CMD ["npm", "start"]