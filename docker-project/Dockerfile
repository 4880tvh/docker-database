# # Dockerfile chính cho các dịch vụ
# # Chỉ định sử dụng docker-compose để xây dựng các dịch vụ

# # Cấu hình cho MySQL
FROM mysql:8.0 AS mysql
ENV MYSQL_ROOT_PASSWORD=example
ENV MYSQL_DATABASE=testdb
ENV MYSQL_USER=user
ENV MYSQL_PASSWORD=password

# # Cấu hình cho PostgreSQL
# FROM postgres:latest AS postgres
# ENV POSTGRES_USER=user
# ENV POSTGRES_PASSWORD=password
# ENV POSTGRES_DB=testdb

# # Cấu hình cho SQL Server
# FROM mcr.microsoft.com/mssql/server:2019-latest AS sqlserver
# ENV ACCEPT_EULA=Y
# ENV SA_PASSWORD=yourStrong(!)Password

# # Cấu hình cho Oracle
# FROM gvenzl/oracle-xe:latest AS oracle
# ENV ORACLE_PASSWORD=password

# # Chỉ định cổng cho các dịch vụ
EXPOSE 3306 

#  5432 1433 1521
