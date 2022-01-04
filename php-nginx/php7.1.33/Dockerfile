FROM dockerskr/alpine:3.15.0-v0.1

COPY alpine-install-pkg /usr/local/bin/
COPY docker-php-* /usr/local/bin/
COPY docker-nginx-* /usr/local/bin/

RUN set -eux; \
    alpine-install-pkg && \
    docker-nginx-compile-install && \
    docker-php-compile-install && \
    echo "done"


