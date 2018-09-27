# Psycopg2 for AWS Lambda

Compile your own

```
docker build -t psycopg2-3.6 -f Dockerfile.36 .
docker run --mount type=bind,src=$(pwd),dst=/opt -it psycopg2-3.6

docker build -t psycopg2-2.7 -f Dockerfile.27 .
docker run --mount type=bind,src=$(pwd),dst=/opt psycopg2-2.7
```

This repo builds and makes available version 2.7.5 of psycopg2