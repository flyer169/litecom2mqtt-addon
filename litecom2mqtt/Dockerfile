ARG BUILD_FROM=ghcr.io/home-assistant/base:latest
FROM $BUILD_FROM

RUN apk add --no-cache nodejs npm

COPY run.sh /

CMD [ "/run.sh" ]
