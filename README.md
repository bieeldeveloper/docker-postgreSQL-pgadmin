# DockerCompose - PostgreSQL - PGAdmin
Docker Compose starts PostgreSQL and PGAdmin

When you start "docker-compose", it will automatically create the "data" folder with postgresql content
### Don't upload data folder 

## Getting Started

### Download source code
    $ git clone https://github.com/bieeldeveloper/docker-postgreSQL-pgadmin.git
    $ cd docker-postgreSQL-pgadmin

### Start Container
    $ docker-compose up -d

### Access PostgreSQL 
    host: localhost:5432
    username: postgres
    password: admin
### Access PgAdmin
    host: http://localhost:15432
    username: admin
    password: admin
* if accessing PostgreSQL from PgAdmin use host "postgres:5432"



## Recommendation

- Docker installation
https://docs.docker.com/install/

