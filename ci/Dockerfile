FROM alpine:3.15.1

ADD fake-gcs-server /bin/fake-gcs-server
ENTRYPOINT ["/bin/fake-gcs-server", "-data", "/data"]
