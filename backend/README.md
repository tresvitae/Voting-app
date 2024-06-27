redis:alpine
postgres:15-alpine
working-app

```
docker pull redis:alpine
docker pull postgres:15-alpine
docker buildx build --platform "linux/arm64/v8" -t worker-app:v1 .
```