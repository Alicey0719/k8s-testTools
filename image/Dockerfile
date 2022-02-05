FROM ubuntu:latest

RUN apt update && \
    apt install -y curl wget mtr iputils-ping net-tools stress && \
    apt clean && \
    rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["tail","-f","/dev/null"]
