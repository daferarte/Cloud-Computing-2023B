FROM node:alpine3.18

RUN mkdir -p /usr/src/app

WORKDIR /usr/src/app

COPY ./app/ .

RUN npm install

EXPOSE 3000

CMD ["npm", "run", "start"]
# CMD ["npm", "run", "dev"]