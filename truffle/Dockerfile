FROM node:7.4-alpine

RUN apk add -t .gyp --no-cache git python g++ make \
    && npm install -g truffle@4.1.7 \
    && apk del .gyp

WORKDIR /apps
ENTRYPOINT ["truffle"]
