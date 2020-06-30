FROM postgres:9.4
ENV POSTGRES_PASSWORD 123
ENV POSTGRES_DB movieinfo
ENV POSTGRES_USER movieinfo
ADD setup.sql /docker-entrypoint-initdb.d
EXPOSE 5432