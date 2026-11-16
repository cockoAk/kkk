# Nginx con Docker Compose

Servidor web nginx corriendo localmente con Docker Compose que sirve un "Hola Mundo".

## Estructura

```
.
├── docker-compose.yml
└── src/
    └── index.html
```

El directorio `src` se monta como volumen en `/usr/share/nginx/html` dentro del contenedor.

## Uso

```bash
docker compose up -d
```

Abrir http://localhost:8080 en el navegador.

Para detenerlo:

```bash
docker compose down
```
