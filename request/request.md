## API Request and Response Documentation

Este archivo documenta cómo interactuar con la API, incluyendo ejemplos de requests y responses.

## Introducción

La API permite interactuar con varios recursos del sistema. A continuación se detallan los endpoints disponibles, cómo realizar los requests y ejemplos de las respuestas que se pueden obtener.

## Endpoints

### 1\. Obtener lista de usuarios

**Método:** `GET`

**Endpoint:**

```plaintext
GET /api/biblioteca
```

```json
[ {
    "status": 200,
    "users": {
            "id": 2,
            "nombre": "Rocio",
            "apellido": "Arruabarrena",
            "email": "rocioa@gmail.com",
            
        },
    }
]
```

```plaintext
{
  "Authorization": "Bearer <token>",
  "Content-Type": "application/json"
}
```