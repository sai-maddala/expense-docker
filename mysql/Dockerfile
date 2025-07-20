FROM mysqL:8.0
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1
# i want to copy all .sql scripts to copy in this location
COPY scripts/*.sql /docker-entrypoint-initdb.d 
# after run the scrpts on above command it will cretae schema and tables 