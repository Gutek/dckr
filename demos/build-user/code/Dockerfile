FROM alpine:latest

# ubuntu
# RUN groupadd -r pd && useradd -r -g pd pd
# alpine
RUN addgroup -S pd && adduser -S pd -G pd
USER pd:pd

CMD id