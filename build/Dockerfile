FROM cassandra:3.11

RUN sed \
    --in-place \
    --expression="s/endpoint_snitch/endpoint_snitch hinted_handoff_enabled/" \
    /usr/local/bin/docker-entrypoint.sh
