FROM alpine:latest
RUN --mount=type=secret,id=pd cat /run/secrets/pd
CMD ls /run/secrets