# Use official MySQL 8.0 image
FROM mysql:8.0

# Set environment variables
ENV MYSQL_ROOT_PASSWORD=Pass@123
ENV MYSQL_DATABASE=mydatabse

# Copy initialization SQL script into container
COPY init.sql /docker-entrypoint-initdb.d/init.sql

# Expose default MySQL port
EXPOSE 3306
