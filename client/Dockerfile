FROM node:14.4.0-alpine3.10

ENV CI=true

WORKDIR /client
COPY package.json .
RUN npm install
COPY . .
RUN npm audit fix

CMD npm run build