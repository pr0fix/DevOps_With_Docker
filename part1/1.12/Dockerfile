FROM node:16

EXPOSE 5000

RUN curl -sL https://deb.nodesource.com/setup_16.x | bash

RUN apt install -y nodejs

RUN node -v && npm -v

COPY package*.json ./

RUN npm install

COPY . .

RUN npm run build

RUN npm install -g serve

CMD ["serve", "-s", "-l", "5000", "build"]