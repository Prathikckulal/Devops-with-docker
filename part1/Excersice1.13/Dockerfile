FROM golang:1.16-alpine

EXPOSE 7089

WORKDIR /usr/src/app

COPY . .

RUN go build

CMD ["./server"]
