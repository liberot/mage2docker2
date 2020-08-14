FROM mariadb:10.4

ENV MYSQL_ALLOW_EMPTY_PASSWORD=1
ENV MYSQL_ROOT_PASSWORD=
ENV MYSQL_PASSWORD=

COPY ./init.sql /docker-entrypoint-initdb.d/init.sql


