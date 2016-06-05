FROM mariadb
COPY initdb.sql /docker-entrypoint-initdb.d/initdb.sql
ENTRYPOINT ["/docker-entrypoint.sh"]

EXPOSE 3306
CMD ["mysqld"]
