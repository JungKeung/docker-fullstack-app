FROM node:10

WORKDIR /app

COPY ./packeage.json ./

RUN npm install

COPY . .

CMD ["npm", "run", "start"];