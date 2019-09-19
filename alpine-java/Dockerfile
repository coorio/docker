FROM alpine:3.9.4

ARG VERSION

RUN apk update --no-cache && \
    apk add openjdk${VERSION}-jre curl && \
    rm -rf /tmp /var/cache

ENTRYPOINT ["java"]
CMD ["-version"]
