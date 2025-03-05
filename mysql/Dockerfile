FROM mysql:8.0
LABEL maintainer="Ravi" \
        version="1.0" \
        description="This is a simple mysql server"
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1
COPY scripts/*.sql /docker-entrypoint-initdb.d