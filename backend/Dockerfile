FROM node:18.0.0

WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install

COPY app.js ./

EXPOSE 3001

CMD ["node", "app.js"]