# go-gql-server

# postgres server

## start server
```
docker run -d --name my_postgres -e POSTGRES_PASSWORD=docker -p 5432:5432 postgres
```
## create database
```
docker exec -it my_postgres psql -U postgres -c "Create database gqltest;"
```