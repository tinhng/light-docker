FROM mariadb:10.3
COPY replication.cnf /etc/mysql/conf.d
COPY eventuate.sql /docker-entrypoint-initdb.d
COPY oauth2.sql /docker-entrypoint-initdb.d
COPY todo_db.sql /docker-entrypoint-initdb.d
COPY saga.sql /docker-entrypoint-initdb.d
COPY saga_example.sql /docker-entrypoint-initdb.d
COPY user_management_ddl.sql /docker-entrypoint-initdb.d
COPY create_tokenization.sql /docker-entrypoint-initdb.d
COPY create_vault.sql /docker-entrypoint-initdb.d
