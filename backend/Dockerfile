FROM node:alpine

WORKDIR /app

COPY ./packeage.json ./

RUN npm install

COPY . .

CMD ["npm", "run", "start"];