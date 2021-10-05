# How to run details service

## Prerequisite

* Ruby 2.7

```bash
ruby details.rb 9080
```

## Build
```bash
docker build -t details .
```

## Run docker
```bash
docker run -d -p 8081:9080 details
```

## How to run with Docker Compose

```bash
docker-compose up
```
