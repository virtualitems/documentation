[volver al inicio](/readme.md)

# Casos de uso

Un caso de uso es una descripción de una acción o actividad que un usuario realiza para lograr un objetivo específico. Cada caso de uso proporciona uno o más escenarios que indican cómo el sistema interactúa con el usuario o con otros sistemas para lograr ese objetivo.

Es importante aclarar que los casos de uso **no describen la funcionalidad interna oculta del sistema ni explican cómo se implementará**. En cambio, simplemente muestran los pasos que el usuario sigue para realizar una tarea.

Cada caso de uso debe ser lo suficientemente sencillo como para que un desarrollador pueda elaborarlo en un solo lanzamiento.

## Actores

Un actor es un rol que desempeña un usuario o un sistema externo que interactúa con el sistema que se está documentando.

Todo caso de uso siempre es iniciado por un actor.

> Ejemplo:
>
> Al usuario administrador se le pueden asignar casos de uso de gestión de usuarios.
>
> Al usuario almacenista se le pueden asignar casos de uso de gestión de productos.

## Relaciones

Los casos de uso pueden relacionarse entre sí con relaciones de inclusión y extensión. La diferencia fundamental entre ambas es que la inclusión es obligatoria y la extensión es opcional.

**Inclusión:** Un caso de uso incluye a otro cuando el primero no puede completarse sin el segundo.

> Ejemplo:
>
> Iniciar sesión → incluye a → Autenticar usuario

**Extensión:** Un caso de uso extiende a otro cuando el primero puede completarse sin el segundo, pero el segundo puede agregar valor al primero.

> Ejemplo:
>
> Listar productos → extiende a → Filtrar productos