
FROM golang:1.20.1-buster 
ADD main.go /
WORKDIR /
RUN go mod init alert_webhook_listener && go build -o main . 
EXPOSE 3010
ENTRYPOINT ["/main"]
