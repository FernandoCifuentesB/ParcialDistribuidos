FROM postgres:16-alpine

ENV  POSTGRES_USER = postgress
ENV POSTGRES_PASSWORD = postgress
ENV POSTGRES_DB = postgress
FROM postgres:16-alpine

COPY init.sql /docker-entrypoint-initdb.d/
