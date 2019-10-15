FROM  postgres:9.5
ENV   POSTGRES_USER postgres
ENV   POSTGRES_PASSWORD postgres
COPY  init.sh /docker-entrypoint-initdb.d
RUN   chmod 777 /docker-entrypoint-initdb.d/init.sh
