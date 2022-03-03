# Based on https://raw.githubusercontent.com/docker-library/php/master/8.1/bullseye/apache/Dockerfile
FROM debian:bullseye-slim
RUN set -eux; \
	apt-get update; \
	apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		xz-utils \
	; \
	rm -rf /var/lib/apt/lists/*