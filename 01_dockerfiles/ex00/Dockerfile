#BUILDING: docker build ./ -t ex00

#RUNNING: docker run -it ex00

FROM alpine:3.4

LABEL author="hrossouw"

RUN apk update && \
    apk add curl && \
    apk add vim

ENTRYPOINT vim