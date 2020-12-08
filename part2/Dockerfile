FROM mysql:latest

COPY ./products.csv /products.csv
COPY ./users.csv /users.csv
COPY ./setup.sql /setup.sql
COPY ./setup1.sql /setup1.sql

ENTRYPOINT ["/entrypoint.sh"]
CMD ["mysqld", "--secure-file-priv=/"]
# CMD ["--secure-file-priv=/"]
