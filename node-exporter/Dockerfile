FROM prom/node-exporter

ENV NODE_ID=none

USER root

COPY conf /etc/node-exporter/

ENTRYPOINT  [ "/etc/node-exporter/docker-entrypoint.sh" ]
CMD [ "/bin/node_exporter" ]

LABEL org.opencontainers.image.source https://github.com/owebboy/swarmprom