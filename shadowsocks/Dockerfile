FROM golang:1.8
ADD . /shadowsocks
RUN go get -v github.com/cssivision/shadowsocks/cmd/server
WORKDIR /shadowsocks
EXPOSE 9983
CMD ["ssserver", "-c", "config.json"]
