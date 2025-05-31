FROM mysql:latest
ENV MYSQL_ROOT_PASSWORD=test
ENV MYSQL_DATABASE=stadium
ENV MYSQL_USER=root
ENV MYSQL_PASWORD=test

COPY stadium.sql /docker-entrypoint-initdb.d/
