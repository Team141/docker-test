FROM mysql:5.7.25

LABEL "Project"="Vprofile"
LABEL "Author"="Kumar raj"

ENV MYSQL_ROOT_PASSWORD = "vpropassdb"
ENV MYSQL_DATABASE = "accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
