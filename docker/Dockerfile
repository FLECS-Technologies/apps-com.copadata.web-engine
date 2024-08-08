ARG ARCH
ARG VERSION
ARG VARIANT

FROM copadata/web-engine:${VERSION}

ARG ARCH
ARG VERSION
ARG VARIANT

RUN [ ! -z "${ARCH}" ]
RUN [ ! -z "${VERSION}" ]

ADD docker/data/ /
