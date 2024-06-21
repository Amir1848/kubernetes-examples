FROM golang:alpine


WORKDIR /APP
COPY main.go .

RUN go build -o /bin/myapp main.go

ENTRYPOINT [ "myapp" ]