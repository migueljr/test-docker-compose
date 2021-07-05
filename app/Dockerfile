FROM node:14.17.1-alpine
WORKDIR /app
COPY ["package.json", "package.lock.json*", "./"]
RUN npm install
RUN npm install nodemon --global
COPY . .
CMD ["npm", "start"]
