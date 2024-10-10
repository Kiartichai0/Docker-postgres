FROM postgres

VOLUME /var/lib/postgresql/data

COPY users.sql ./

EXPOSE 5432

ENV POSTGRES_PASSWORD=password
ENV POSTGRES_DB=postgres
ENV POSTGRES_USER=postgres