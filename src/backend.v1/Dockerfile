FROM golang:1.14
WORKDIR /go/src/app
COPY . .

RUN go get -d -v ./...
RUN go install -v ./...


# This command starts up the app
ENTRYPOINT ["/usr/local/go/bin/go run /go/src/app"]