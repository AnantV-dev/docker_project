FROM mysql
# Add a database
ENV MYSQL_DATABASE BHARATINDEX
ENV MYSQL_ROOT_PASSWORD=root


COPY . .
# Add the content of the sql-scripts/ directory to your image
# All scripts in docker-entrypoint-initdb.d/ are automatically
# executed during container startup
COPY BHARATINDEX_schema.sql /docker-entrypoint-initdb.d/
