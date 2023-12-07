FROM debian:11 AS os-build

# Copy the setup folder onto the container
COPY build/ /tmp/build/

# Setup the container for the build
RUN apt update && apt install -y live-build rsync nginx qemu-system-x86 patch
