FROM golang:1.7

ENV GOPATH /go
ENV SERVPATH /go/src/signup

RUN mkdir -p $SERVPATH
WORKDIR $SERVPATH

COPY . $SERVPATH
RUN cd $SERVPATH && go build

EXPOSE 3001

ENTRYPOINT ["/go/src/signup/signup"]
