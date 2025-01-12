FROM alpine:3.21.2

RUN apk add --no-cache \
    curl \
    jq

CMD exec /bin/sh -c "trap : TERM INT; (while true; do sleep 1000; done) & wait"