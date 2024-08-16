[volver al inicio](/readme.md)

[volver a implementación](/docs/phases/implementation.md)

# Control de versiones con Git

Git es un sistema de control de versiones distribuido que permite llevar un registro de los cambios realizados en el código fuente de un proyecto. Estos cambios se guardan en un repositorio, que es una base de datos que almacena los archivos y carpetas del proyecto, así como el historial de cambios.

<br>

## Repositorio

Un repositorio es una base de datos que almacena los archivos y carpetas del proyecto, así como el historial de cambios. Existen dos tipos de repositorios: locales y remotos.

**Repositorio local:** Es un repositorio que se encuentra en la computadora del desarrollador. Se utiliza para trabajar en el proyecto y guardar los cambios realizados.

**Repositorio remoto:** Es un repositorio que se encuentra en un servidor. Se utiliza para compartir el proyecto con otros desarrolladores y para hacer copias de seguridad.

<br>

## Ramas

Una rama es una línea de desarrollo independiente que permite trabajar en el proyecto sin afectar el código de la rama principal. Cada rama tiene un nombre y un punto de inicio, que es el commit del que se creó.

Existen diferentes flujos de trabajo con diferentes criterios para crear y fusionar ramas. Los flujos de trabajo más comunes son:

- Main (Master) only
- Git flow
- Github flow
- Gitlab flow
- One flow

<br>

## Commits

Los commits son registros de los cambios en el código fuente de un proyecto. Cada commit tiene un identificador único, un autor, una fecha y un mensaje.

El mensaje de un commit debe ser breve y descriptivo con un máximo de 50 caracteres y estar escrito en minúsculas. Debes escribir en tiempo pasado y no terminar en punto final.

Debes seguir el siguiente formato:

```
<tipo> <complemento>

<detalles>
```

**&lt;tipo&gt;** Indica el tipo de cambio realizado usando un verbos en tiempo pasado.

- creado: se han creado nuevos archivos.
- actualizado: se han actualizado archivos existentes.
    - agregado: se ha agregado contenido.
    - cambiado: se ha cambiado contenido.
    - quitado: se ha quitado contenido.
    - renombrado: se ha renombrado contenido.
- reemplazado: se han reemplazado archivos.
- eliminado: se han eliminado archivos.
- corregido: se han corregido errores.
- reestructurado: se ha reestructurado código.
- renombrado: se han renombrado archivos.
- movido: se han movido archivos.
- mejorado: se ha mejorado código.

**&lt;complemento&gt;** Indica el elemento modificado y en qué condiciones se modificó. Omite los artículos para acortar el mensaje, sólo menciona el sustantivo.

**&lt;detalles&gt;** Agrega información opcional que ayude a entender el cambio realizado o por qué se hizo.

> Ejemplo:
>
> creado archivo readme.md
>
> se agregó toda la información del proyecto y la lista de contribuidores.

<br>

## Consideraciones

1. Se debe hacer un commit que represente cada tarea finalizada, pero esto no significa que no se puedan hacer otros commits durante el desarrollo de la tarea.

2. Es una buena práctica durante la definición de tareas escribir los mensajes de los commits que se harán para cada tarea.