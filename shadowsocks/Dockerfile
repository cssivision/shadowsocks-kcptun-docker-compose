FROM golang:1.8
ADD . /shadowsocks
RUN go get -v github.com/shadowsocks/shadowsocks-go/cmd/shadowsocks-server
WORKDIR /shadowsocks
EXPOSE 1908 9983
CMD ["shadowsocks-server", "-c", "config.json"]
