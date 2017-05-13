FROM golang:1.8
ADD . /kcptun
RUN go get -v github.com/xtaci/kcptun/server
WORKDIR /kcptun 
EXPOSE 2006/udp
CMD ["server", "-c", "config.json"]
