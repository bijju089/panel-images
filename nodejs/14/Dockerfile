FROM        node:14-bullseye-slim

LABEL       author="Bijju089" maintainer="me@bijjuxd.me"
LABEL       org.opencontainers.image.source="https://github.com/bijju089/panel-images"
LABEL       org.opencontainers.image.licenses="MIT"

RUN         apt update \
            && apt -y install ffmpeg iproute2 git sqlite3 libsqlite3-dev python3 python3-dev ca-certificates dnsutils tzdata zip tar curl build-essential libtool iputils-ping libnss3 tini \
			&& useradd -m -d /home/container container

RUN         npm install npm@9.8.1 typescript ts-node @types/node --location=global

USER        container
ENV         USER=container HOME=/home/container
WORKDIR     /home/container

STOPSIGNAL  SIGINT

COPY        --chown=container:container ./../entrypoint.sh /entrypoint.sh
RUN         chmod +x /entrypoint.sh
ENTRYPOINT    ["/usr/bin/tini", "-g", "--"]
CMD         ["/entrypoint.sh"]
