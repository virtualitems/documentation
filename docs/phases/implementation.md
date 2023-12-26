[volver al inicio](/readme.md)

# Fase de seguimiento de la implementación

Durante la implementación de la solución se debe hacer un seguimiento del avance del proyecto y el trabajo realizado mediante el uso de herramientas de control de versiones y gestión de tareas.

El seguimiento de la implementación se divide en dos partes: el seguimiento de las tareas y el seguimiento de los cambios en el código fuente.

<br/>


## Tareas y commits

Las tareas son los objetivos que se deben cumplir para completar la fase de implementación, y los commits son registros de los cambios en el código fuente. Cada tarea debe tener un commit asociado, así como un mensaje que se guardará en el repositorio. Este mensaje debe describir los cambios realizados usando el formato:

```
<tipo>: <descripción>

<detalles>
```

<br/>

El **tipo** del commit indica el tipo de cambio realizado. Los tipos de commit son:

- bug: se corrigió un error.
- configuration: cambios en la configuración, dependencias o herramientas de construcción.
- docs: cambios en la documentación.
- feat: se agregó una nueva característica.
- performance: mejoras en el rendimiento.
- refactor: se reestructuró el código sin agregar o quitar funcionalidades.
- style: cambios en la interfaz de usuario.
- test: cambios en las pruebas automatizadas.


<br/>

La **descripción** inicial del commit es un título que sirve para identificar el cambio al leer el historial o buscar un commit en particular. Debe ser breve con un máximo de 50 caracteres y estar escrito en minúsculas. Se debe usar el tiempo pasado y no debe terminar con un punto.

Para facilitar la navegación, se recomienda que la primera palabra sea estándar según el cambio:

- creado: se han creado nuevos archivos.
- actualizado: se han actualizado archivos existentes.
- - agregado: se ha agregado contenido.
- - cambiado: se ha cambiado contenido.
- - quitado: se ha quitado contenido.
- - renombrado: se ha renombrado contenido.
- reemplazado: se han reemplazado archivos.
- eliminado: se han eliminado archivos.
- corregido: se han corregido errores.
- reestructurado: se ha reestructurado código.
- renombrado: se han renombrado archivos.
- movido: se han movido archivos.
- mejorado: se ha mejorado código.

<br/>


### Ejemplo de commit

```
docs: creado el archivo readme.md

Se creó el archivo readme.md con la descripción del proyecto.
```


### Consideraciones

- Se debe hacer un commit que represente la tarea finalizada, pero esto no significa que no se puedan hacer otros commits durante el desarrollo de la tarea.
- Es una buena práctica durante la definición de tareas escribir los mensajes de los commits que se harán para cada tarea.


<br/>

## Docstrings

Los docstrings son comentarios que se agregan al código para documentar su funcionamiento. Estos comentarios deben ser agregados a funciones, métodos y clases.

[ver más](../textos/c%C3%B3digo.md#docstrings)


## Artefacto

La documentación de esta fase son el registro de tareas, el historial de versiones y los docstrings.