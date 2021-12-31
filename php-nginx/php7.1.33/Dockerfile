FROM dockerskr/alpine:phpbase-v0.1

COPY php-7.1.33.tar.gz /
COPY alpine-install-pkg /usr/local/bin/
COPY docker-php-* /usr/local/bin/
COPY docker-nginx-* /usr/local/bin/

RUN set -eux; \
#alpine-install-pkg && \
    docker-nginx-compile-install && \
#docker-php-compile-install && \
    echo "hahahahahaha"


