FROM dockerskr/alpine:phpbase-v0.1

COPY php-7.1.33.tar.gz /
COPY docker-php-* /usr/local/bin/

RUN set -eux; \
    PHP_INSTALL_PATH="/usr/local/matrix" && \
    docker-php-compile-install && \
    echo "hahahahahaha"


