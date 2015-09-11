FROM ghmlee/scratch:latest
MAINTAINER Graham Lee <ghmlee@ghmlee.com>

ENV PORT 8888

ADD . /mongodb-rest-api

EXPOSE 8888

WORKDIR /mongodb-rest-api
ENTRYPOINT ["./mongodb-rest-api"]