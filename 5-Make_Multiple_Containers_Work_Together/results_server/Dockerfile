FROM node:8.16-alpine3.9

RUN mkdir -p /src/app

WORKDIR /src/app

COPY . /src/app

RUN yarn install

RUN yarn global add nodemon

EXPOSE 3000

CMD [ "npm", "run", "startdev" ]