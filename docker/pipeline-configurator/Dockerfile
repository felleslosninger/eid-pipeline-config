FROM docker:19.03.12

COPY run /usr/local/bin/
COPY config.yaml /config.yaml
COPY jobs.yaml /jobs.yaml
RUN chmod a+x /usr/local/bin/run

ENTRYPOINT /usr/local/bin/run