FROM pingcap/alpine-glibc

ADD bin/tikv-importer /tikv-importer

RUN chmod +x /tikv-importer

WORKDIR /

EXPOSE 8808

ENTRYPOINT ["/tikv-importer"]



