FROM mysql:latest
ENV MYSQL_ROOT_PASSWORD=fernanda
ENV MYSQL_DATABASE=stadium
ENV MYSQL_USER=fernanda
ENV MYSQL_PASSWORD=fernanda

COPY stadium.sql /docker-entrypoint-initdb.d/
