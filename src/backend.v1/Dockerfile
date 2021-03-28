FROM golang:1.16.2-buster AS base
WORKDIR /go/src/app
COPY . .

RUN go get -d -v ./...
RUN go install -v ./...

CMD ["app"]


# This command starts up the app
#ENTRYPOINT ["/app/bin/server"]