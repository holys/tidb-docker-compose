FROM pingcap/rust:latest

ADD bin/tikv-importer /tikv-importer

RUN chmod +x /tikv-importer

WORKDIR /

EXPOSE 8808

ENTRYPOINT ["/tikv-importer"]



