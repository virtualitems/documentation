[volver al inicio](/readme.md)

[volver a implementación](/docs/phases/implementation.md)

# API web

A continuación se listan los datos recomendados para la especificación.

<br>

## Request

- HTTP version
- HTTP method
- URL
- Authorization method
- Query parameters
- Request headers
- Request body
    - none
    - application/json
    - application/octet-stream
    - application/x-www-form-urlencoded
    - multipart/form-data
    - text/xml
- Cookies

<br>

## Success response

- Status code
    - 200 (listar recursos o buscar un recurso)
    - 201 (crear un recurso)
    - 202 (ejecución asincrona iniciada con éxito)
    - 204 (actualizar o eliminar un recurso)
- Status message
- Response headers
- Response body
- Cookies

<br>

## Error response

- Status code
    - 400 (falló en la validación de datos de la petición)
    - 401 (acción sin autorización)
    - 403 (acción prohibida)
    - 404 (la ruta o el detalle del recurso no existe)
    - 405 (método http no permitido)
    - 409 (hubo un conflicto al procesar la petición)
    - 500 (error interno del servidor)
- Status message
- Response headers
- Response body
- Cookies