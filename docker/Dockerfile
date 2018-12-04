FROM busybox:1.29

ENV PG_VERSION=10 

RUN apt-get update \
 && DEBIAN_FRONTEND=noninteractive apt-get install -y acl sudo \
    postgresql-client-${PG_VERSION} mysql-client cron vim

VOLUME ["/backupdata"]vim