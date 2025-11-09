FROM node:16

WORKDIR /usr/app

COPY package*.json .

RUN npm install --prefix ./express-app

COPY . .

CMD ["node", "index.js"]