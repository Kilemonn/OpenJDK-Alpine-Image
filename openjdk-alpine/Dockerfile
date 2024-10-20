# Build image with tag
# docker build -t kilemon/openjdk-alpine:alpine-3.20.0-jdk-17.0.11 .
# docker tag kilemon/openjdk-alpine:alpine-3.20.0-jdk-17.0.11 kilemon/openjdk-alpine:latest
#
# Push image to remote
# docker push kilemon/openjdk-alpine:alpine-3.20.0-jdk-17.0.11

FROM alpine:3.20.3

RUN apk update && apk upgrade && apk add openjdk21

# ENV JAVA_HOME=/usr/local/openjdk-17
# ENV PATH=/usr/local/openjdk-17/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
ENV LANG=C.UTF-8

# Check the actual java version and update
ENV JAVA_VERSION=21.0.4+7

CMD [ "jshell" ]
