FROM golang:1.12.14 AS base
RUN add-apt-repository ppa:longsleep/golang-backports
RUN go run .
RUN go build -i -o ./bin/server
RUN chmod +x ./bin/server
RUN ./bin/server


# This command starts up the app
ENTRYPOINT ["/app/bin/server"]