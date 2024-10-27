FROM debian:bookworm

RUN apt-get update -y && apt-get install build-essential gdb nasm vim -y

# recreate group and user with the same UID e GID from host
RUN groupadd -g 1000 llp && useradd -r -u 1000 -g llp llp


USER llp


