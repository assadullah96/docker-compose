FROM golang:1.12.0-alpine3.9

RUN mkdir /app

ADD golang-webserver /app

WORKDIR /app

RUN chmod +x golang-webserver

EXPOSE 8080

CMD ["/app/golang-webserver"]
