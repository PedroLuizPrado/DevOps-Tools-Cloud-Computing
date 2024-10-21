FROM node:20

RUN mkdir -p /usr/src/app
WORKDIR /usr/stc/app

COPY package.json .

RUN npm install express

COPY ./ .

EXPOSE 3031

CMD ["node","index.js"]