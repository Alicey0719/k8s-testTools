FROM ubuntu:latest

RUN apt update && \
    apt install -y curl wget mtr htop iputils-ping net-tools dnsutils stress && \
    apt clean && \
    rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["tail","-f","/dev/null"]
