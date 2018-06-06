FROM pingcap/rust:latest

ADD bin/tikv-server /tikv-server

RUN chmod +x /tikv-server

WORKDIR /

EXPOSE 20160

ENTRYPOINT ["/tikv-server"]
