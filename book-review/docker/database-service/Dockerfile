FROM mysql:latest

ENV MYSQL_ROOT_PASSWORD: 123456
ENV MYSQL_DATABASE: book_review_db
ENV MYSQL_USER: root
ENV MYSQL_PASSWORD: 123456

ADD setup.sql /docker-entrypoint-initdb.d
