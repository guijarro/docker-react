FROM node:alpine
WORKDIR '/app'
COPY ./index.js ./
COPY ./keys.js ./
COPY ./package.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "start"]
