FROM       openjdk:17-slim

LABEL       author="Joss Bird" maintainer="joss@disparity.host"

LABEL       org.opencontainers.image.source="https://github.com/slack69/hosting-node-container"

RUN 		apt-get update -y \
 			&& apt-get install -y curl ca-certificates openssl git tar sqlite3 fontconfig libfreetype6 tzdata iproute2 libstdc++6

WORKDIR		/home/container