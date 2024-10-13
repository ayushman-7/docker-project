FROM mysql:8.0.33
LABEL "Project"="Docker Project"
LABEL "Author"="Ayushman"

ENV MYSQL_ROOT_PASSWORD="amt@123"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql
