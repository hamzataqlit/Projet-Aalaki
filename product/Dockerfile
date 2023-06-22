FROM node:alpine

ENV NODE_ENV=production

WORKDIR /app

COPY ["package.json", "package-lock.json*", "./"]

RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "run", "server"]