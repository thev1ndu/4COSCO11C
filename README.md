```
docker build -t web:latest .
```

```
docker run -d -p 80:80 --name web web:latest
```

or 

```
docker-compose build
```

```
docker-compose up -d
```
