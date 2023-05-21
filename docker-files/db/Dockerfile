FROM mysql:latest
RUN apt update
LABEL "Project":"Vprofile"
ENV   MYSQL_ROOT_PASSWORD="vprodbpass"
ENV   MYSQL_DATABASE="accounts"
ADD /vprofile-project/src/main/resources/db_backup.sql ./docker-entrypoint-initdb.d
