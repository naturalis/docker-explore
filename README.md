# docker-explore


## Overview
Explore

## Usage
Install Docker. Clone this repo to your local machine. Create network, to be able to run more postgres instances on the same network.

```bash
docker network create pgnet
docker-compose up
```

### Open pgAdmin webinterface
```bash
[pgadmin]: http://pgadmin.docker.localhost/
```
Database, username and password: postgres

### Connect to Postgres container
     docker exec -it dockerpostgresplus_postgres_1 sh (or docker-compose exec postgres sh)
     su
     docker-compose exec postgres psql -U postgres
