FROM docker:17.12.0-ce

COPY run /usr/local/bin/
COPY config.yaml /config.yaml
COPY jobs.yaml /jobs.yaml
RUN chmod a+x /usr/local/bin/run

ENTRYPOINT /usr/local/bin/run