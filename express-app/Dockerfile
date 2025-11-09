FROM node:16

WORKDIR /usr/app

COPY . .

RUN ls -al

RUN npm install --prefix ./express-app

CMD ["node", "index.js"]