## docker

### docker intialising new db container for postgres

```
docker run --name pg_database -p 5432:5432 -e POSTGRES_PASSWORD=yourpassword -d postgres:latest
```
