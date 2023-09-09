FROM  postgres:14-alpine

COPY init-db.sh /docker-entrypoint-initdb.d/init-db.sh
COPY seed-bdd /seed-bdd

RUN chmod +x /docker-entrypoint-initdb.d/init-db.sh

EXPOSE 5432


