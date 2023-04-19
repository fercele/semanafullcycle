FROM golang:1.20 AS build

WORKDIR /usr/src/app

COPY go.mod .

COPY *.go .

RUN go build -o /usr/local/bin/atividade1

FROM scratch

COPY --from=build /usr/local/bin/atividade1 /atividade1

ENTRYPOINT ["/atividade1"]

