FROM node:18
# FROM node:14

WORKDIR /usr/src/app
# COPY package*.json ./
COPY . .
# RUN npm install
RUN yarn install --frozen-lockfile

# EXPOSE 5173

CMD ["npm", "run", "dev"]