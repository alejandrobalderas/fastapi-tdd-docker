# pull official base image
FROM postgres:13-alpine

# run create.sql on init
# by adding create.sql to the "docker-entrypoint-initdb.d" directory in the container. 
# This file will execute on init.
ADD create.sql /docker-entrypoint-initdb.d