FROM node:22

WORKDIR /home/app

COPY package*.json ./
RUN npm i

COPY server.js ./

CMD ["npm", "start"]
