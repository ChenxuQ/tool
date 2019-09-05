FROM alpine:latest

RUN apk add --update --no-cache openjdk8 && \
    apk add --update --no-cache tzdata && \
    cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime && \
    apk del --purge tzdata
