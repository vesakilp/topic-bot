FROM node:4-onbuild

RUN mkdir /src

RUN npm install nodemon -g

WORKDIR /src

ADD app.js /src/app.js

ADD package.json /src/package.json

RUN npm install

EXPOSE 8080

CMD npm start
