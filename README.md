# Postgresql

- createuser flask --interactive --password. Set to b52l0bster. Then change /var/lib/pgsql/data/pg_hba.conf and change ident authentication to password
- then using postgres user CREATE ROLE flask WITH CREATEDB LOGIN USER flask PASSWORD 'b52l0bster'; also CREATE DATABASE base_app OWNER flask;

//TODO docker file this! 

