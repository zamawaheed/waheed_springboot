FROM postgres:9.6
ARG POSTGRES_USER=postgres
ARG POSTGRES_PASSWORD=postgres
COPY init_ddl.sh /docker-entrypoint-initdb.d/
RUN chmod +x /docker-entrypoint-initdb.d/init_ddl.sh


