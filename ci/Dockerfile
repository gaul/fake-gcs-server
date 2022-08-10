FROM alpine:3.16.2

ADD fake-gcs-server /bin/fake-gcs-server
ENTRYPOINT ["/bin/fake-gcs-server", "-data", "/data"]
