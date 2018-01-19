FROM alpine:latest
MAINTAINER @ernezto

ENV TERM=xterm-256color

RUN apk update; apk upgrade; apk add mcabber
RUN mkdir -p ~/.mcabber/history/
RUN mkdir -p ~/.mcabber/otr/
