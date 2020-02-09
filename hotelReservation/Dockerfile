FROM golang:1.9

COPY . /go/src/github.com/Fatahir/ds/tree/master/hotelReservation
WORKDIR /go/src/github.com/github.com/Fatahir/ds/tree/master/hotelReservation
RUN go get gopkg.in/mgo.v2
RUN go get github.com/bradfitz/gomemcache/memcache
RUN go install -ldflags="-s -w" ./cmd/...
