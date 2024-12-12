FROM postgres:13-alpine

COPY init.sql /docker-entrypoint-initdb.d/init.sql
#COPY postgresql.conf /etc/postgresql/postgresql.conf

EXPOSE 5432