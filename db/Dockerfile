FROM mysql:8.0-bookworm

COPY ./database.sql /docker-entrypoint-initdb.d/database.sql
COPY ./exporter_user.sql /docker-entrypoint-initdb.d/exporter_user.sql

EXPOSE 3306 33060