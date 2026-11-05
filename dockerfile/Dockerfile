FROM golang:1.27.3-alpine3.24

RUN apk add --no-cache ca-certificates curl gnupg

RUN mkdir -p /opt/node-app

WORKDIR /opt/node-app

COPY index.js .

EXPOSE 80

CMD ["node", "index.js"]