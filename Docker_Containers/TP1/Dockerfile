FROM postgres:17.2-alpine

ENV POSTGRES_PASSWORD=password
ENV POSTGRES_HOST_AUTH_METHOD=trust

COPY docker-entrypoint-initdb.d/ /docker-entrypoint-initdb.d/
