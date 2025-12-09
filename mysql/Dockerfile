FROM mysql:8.0

ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=logistics_db

COPY Logistic_db.sql /docker-entrypoint-initdb.d/

EXPOSE 3306
