# Development

1. Run Proyect 
   
```bash
docker-compose up --build -d
```

2. Generate migrations

```bash
docker compose exec diiwo_backend python manage.py makemigrations
docker compose exec diiwo_backend python manage.py migrate
```