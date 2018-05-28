ARG BUILD_FROM=amd64/alpine:3.7
FROM ${BUILD_FROM}

# Setup Qemu
ARG QEMU_ARCH
COPY tmp/qemu-${QEMU_ARCH}-static /usr/bin/qemu-${QEMU_ARCH}-static
RUN ls -al /usr/bin/
