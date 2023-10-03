FROM ghost:5-alpine

RUN apk --no-cache add shadow \
    && usermod -u 1001 node \
    && groupmod -g 1001 node
