### How to build and run application

1. Build image for UI 
```
docker build -t cvat/ui:latest -f Dockerfile.ui .
```
2. Build image for server
```
docker build -t cvat/server:latest . 
```
3. Compose and run application on localhost:8080
```
docker compose up -d
```
