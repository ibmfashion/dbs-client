FROM ubuntu:bionic

ENV PG_VERSION=10 

RUN apt-get update \
 && DEBIAN_FRONTEND=noninteractive apt-get install -y acl sudo \
postgresql-client-${PG_VERSION} mysql-client cron vim mongodb


VOLUME ["/backupdata"]
