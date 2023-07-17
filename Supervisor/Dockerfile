FROM ubuntu:20.04

WORKDIR /app

RUN apt-get update &&\
  apt install -y supervisor

COPY worker.conf /etc/supervisor/conf.d/

RUN touch sample.py

CMD ["/usr/bin/supervisord"]
