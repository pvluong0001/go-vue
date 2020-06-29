FROM golang:1.14

WORKDIR /go/src/app

RUN go get "github.com/go-sql-driver/mysql"
RUN go get "github.com/gorilla/mux"
RUN go get "github.com/cosmtrek/air"

COPY ./air .
RUN chmod a+x ./air