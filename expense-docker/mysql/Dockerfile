FROM mysql:8
ENV MYSQL_ROOT_PASSWORD=ExpenseAPP@1 \
    MYSQL_USER=expense \
    MYSQL_ROOT_PASSWORD=ExpenseApp@1 \
    MYSQL_DATABASE=transactions
COPY scripts/*.sql /docker-entrypoint-initdb.d/