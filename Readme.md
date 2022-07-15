## docker

### docker intialising new db container for postgres

```
docker run --name pg_database -p 5432:5432 -e POSTGRES_PASSWORD=yourpassword -d postgres:latest
```
open  docker desktop to see the server running.

### connectingn to postgres

```
psql --host localhost --port 5432 --dbname postgres --username postgres
```
