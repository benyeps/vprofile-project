FROM mysql:8.0.33
LABEL "Projec"="Vprofile"
LABEL "Author"="Benjamin"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sh