# Usage

```
docker build -t bugg-go:local .
docker run --rm -p 8080:8080 --name bugg-go -it bugg-go:local
curl 'http://localhost:8080/hello'
```

Why this does not work?

