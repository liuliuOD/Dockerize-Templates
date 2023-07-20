FROM ubuntu:20.04

ARG VERSION

WORKDIR $VERSION

RUN apt update -y \
    && apt install -y siege=$VERSION \
    && apt clean

ENTRYPOINT ["siege"]
CMD ["--help"]
