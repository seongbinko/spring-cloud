FROM mysql:5.7
ENV MYSQL_ALLOW_EMPTY_PASSWORD=true
ENV MYSQL_DATABASE msa_test_db
# ADD ./mysql_data/mysql /var/lib/mysql
EXPOSE 3306
# --initialize-insecure (blank root password)
# ENTRYPOINT ["mysqld", "--user=root"]
CMD [ "mysqld"]