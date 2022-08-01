# fastapi-project
A simple example of using Fast API. E-mail classification as a ML model is implemented as a showcase


## Build docker images
```
docker-compose build
```

## launch the stack
```
docker-compose up -d
```

## Service in stack - Port Mappings
| Service | Port | URL |
| --- | --- | --- |
| Airflow | 8080 | [Airflow](http://localhost:8080/admin/) |
| FastApi | 8000 | [FastApi](http://localhost:80/docs/) |
| Jupyter | 8888 | [Jupyter](http://localhost:8888/) |
| Minio | 9000 | [Minio](http://localhost:9000/minio/) |
| Portainer | 9090 | [Portainer](http://localhost:9090/) |
| Postgres | 5432 | - |
| Superset | 8088 | [Superset](http://localhost:8088/login/) |
| pgAdmin 4 | 5050 | [pgAdmin 4](http://localhost:5050/login?next=%2F) |
