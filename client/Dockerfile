FROM node:14-alpine

WORKDIR /opt/app
COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]