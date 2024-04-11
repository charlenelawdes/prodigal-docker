FROM ubuntu:23.10

RUN apt-get update && apt-get install -y \
    build-essential \
    git \
    zlib1g-dev

RUN git clone https://github.com/hyattpd/Prodigal
WORKDIR Prodigal
RUN make
RUN make install
