FROM golang:1.14

WORKDIR /opt/client-api

COPY . .

RUN go build -o app main.go

CMD ["/opt/client-api/app"]