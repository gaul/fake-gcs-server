FROM alpine:3.15.4

ADD fake-gcs-server /bin/fake-gcs-server
ENTRYPOINT ["/bin/fake-gcs-server", "-data", "/data"]
