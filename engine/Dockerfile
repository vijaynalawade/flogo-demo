FROM alpine:3.7
WORKDIR /app
ADD engine-linux-amd64 /app/flogoengine
RUN chmod 777 /app/flogoengine
ENV FLOGO_HTTP_SERVICE_PORT=7777
EXPOSE 7777
ENTRYPOINT ["/app/flogoengine"]