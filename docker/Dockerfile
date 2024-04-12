FROM debian:bullseye

RUN apt-get update && apt-get install -y \
    build-essential \
    gcc \
    git \
    zlib1g-dev

RUN git clone https://github.com/hyattpd/Prodigal
WORKDIR Prodigal
RUN make
RUN make install
