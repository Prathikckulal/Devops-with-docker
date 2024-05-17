FROM node:14-alpine

EXPOSE 2010

WORKDIR /usr/src/app

COPY . .

ENV REACT_APP_BACKEND_URL=http://localhost:7089

RUN npm install

RUN npm run build

RUN npm install -g serve

CMD ["serve", "-s", "-l", "2010", "build"]
