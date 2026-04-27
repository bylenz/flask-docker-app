# flask-docker-app

Aplicación Flask containerizada con Docker — práctica de DevOps.

## Estructura

```
flask-docker-app/
├── app.py
├── requirements.txt
├── Dockerfile
└── .dockerignore
```

## Uso

```bash
docker build -t flask-docker-app .
docker run -p 5000:5000 flask-docker-app
```

Luego abrí http://localhost:5000

## Endpoints

- `/` — página principal
- `/api/health` — estado de la API
- `/api/info` — información del contenedor
