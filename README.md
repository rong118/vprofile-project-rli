# README

This project is forked from `hkhcoder/vprofile-project` as resource for personal DevOps projects

## Prerequisites

### JDK/Server/Web framework/Database
- JDK 11
- Maven 3
- MySQL 8
- Spring MVC
- Spring Security
- Spring Data JPA
- JSP
- Tomcat
- MySQL
- Memcached
- RabbitMQ
- Elasticsearch

## Database Setup

We use MySQL for the database. To import the SQL dump file:

1. Locate the SQL dump file at `/src/main/resources/db_backup.sql`.
2. Use the following command to import the dump into your MySQL database:
   ```sh
   mysql -u <user_name> -p accounts < /src/main/resources/db_backup.sql
   ```