FROM node:argon
EXPOSE 80

LABEL MAINTAINER=DDU

WORKDIR /app
COPY package.json .
RUN npm install
COPY . .

CMD ["node", "server.js"]
