FROM golang:latest
WORKDIR /go/src

COPY go.mod /go/src/go.mod
COPY go.sum /go/src/go.sum
WORKDIR /go/src
RUN ls
RUN go mod download

COPY . /go/src