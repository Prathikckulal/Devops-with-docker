FROM golang:1.16-alpine

EXPOSE 7089

WORKDIR /usr/src/app

COPY . .

ENV REQUEST_ORIGIN=http://localhost:2010

RUN go build

CMD ["./server"]
