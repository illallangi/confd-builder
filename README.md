# Confd

Confd, for use in other docker images

## Usage

    # main image
    FROM docker.io/library/debian:latest
    
    # install confd
    COPY --from=ghcr.io/illallangi/confd-builder:latest /go/bin/confd /usr/local/bin/confd
