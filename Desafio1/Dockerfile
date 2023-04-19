FROM golang:1.20

WORKDIR /usr/src/app

COPY go.mod .

COPY *.go .

RUN go build -o /usr/local/bin/atividade1

CMD ["atividade1"]

