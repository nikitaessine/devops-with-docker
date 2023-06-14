terminaali 1

```bash
docker build -f frontend-example -t node-frontend
docker run -p 5000:5000 node-frontend
```

terminaali 2

```bash
docker build -f backend-example -t go-backend

docker run -p 8080:8080 go-backend

```
