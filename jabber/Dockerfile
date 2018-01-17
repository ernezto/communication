FROM alpine:latest
MAINTAINER @ernezto

RUN apk update; apk upgrade; apk add mcabber
RUN mkdir -p ~/.mcabber/history/
RUN mkdir -p ~/.mcabber/otr/
COPY mcabberrc ~/.mcabber/mcabberrc
CMD mcabber ~/.mcabber/mcabberrc
