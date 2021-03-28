FROM golang:1.14
WORKDIR /go/src/app
COPY . .

RUN go get -d -v ./...
RUN go install -v ./...

CMD ["app"]


# This command starts up the app
#ENTRYPOINT ["/app/bin/server"]