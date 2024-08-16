[volver al inicio](/readme.md)

# Fase de implementación

La fase de implementación de la documentación de software se enfoca en la descripción de los detalles técnicos del sistema.

Generalmente está dividida en dos partes: la planeación de la implementación y el seguimiento de la implementación.

<br>

# Planeación de la implementación

Durante la planeación de la implementación se crean documentos que describen cómo se construirá y cómo funcionará el sistema internamente.

A continuación se listan los documentos recomendados para la planeación de la implementación:

<br>

## Topología

La topología describe la infraestructura tecnológica que soporta al sistema así como los proyectos instalados en ella. Generalmente incluye información acerca de servidores, instancias o maquinas virtuales, sistemas operativos, software instalado, bases de datos, puertos y protocolos, redes, etc.

<br>

## Componentes de software

Los componentes de software son agrupaciones lógicas de código que pueden funcionar de manera independiente.

> Por ejemplo, se puede dividir un sistema por:
> - capas según la arquitectura
> - archivos y directorios
> - rutas de navegación (url)

<br>

## Diagramas de bases de datos

Los diagramas de bases de datos son la especificación visual de cómo se almacenan los datos en el sistema.

Depende de la tecnología utilizada para el almacenamiento de datos varía el diagrama que se debe utilizar.

_Nota: Diagrama Entidad-Relación **no** es lo mismo que Diagrama Relacional. Para una base de datos relacional se usa un diagrama relacional._

<br>

## Especificación de APIs

La especificación de APIs detalla la capa de transmisión de datos entre diferentes sistemas. También detalla cómo se comunican los diferentes componentes del sistema internamente.

A continuación se listan los datos recomendados para cada tipo de API:
- [API librería](/docs/api/library.md)
- [API web](/docs/api/web.md)

<br>

## Algoritmos de servicios

La documentación de algoritmos de servicios especifica paso a paso cómo se ejecuta un proceso del sistema desde que el usuario o actor principal inicia un caso de uso hasta que se completa.

Los algoritmos generalmente se documentan mediante diagramas de flujo, diagramas de secuencia o diagramas de actividades.

<br>

## Lista de nuevos permisos

Como buena práctica se recomienda documentar los nuevos permisos que se crean en cada desarrollo.

La lista de permisos generalmente sólo contiene el nombre del permiso, el perfil al que pertenece y las acciones permitidas.

**Perfiles y Roles**
- Un perfil es un conjunto de autorizaciones que se le asignan a un usuario mediante un rol.
- Los roles son un conjunto de perfiles que le son asignados al usuario para que pueda realizar sus actividades.

<br>

# Seguimiento de la implementación

Durante la implementación de la solución se debe hacer un seguimiento del avance del proyecto y el trabajo realizado mediante el uso de herramientas de control de versiones y gestión de tareas.

El seguimiento de la implementación implica:
- [Seguimiento de tareas](/docs/coding/tasks.md)
- [Seguimiento de cambios en el código fuente](/docs/coding/git.md)

<br/>

## Docstrings

Los docstrings son comentarios que se agregan al código para documentar su funcionamiento. Estos comentarios deben ser agregados a archivos, variables, funciones, clases, atributos y métodos.

[ver más](/docs/coding/docstrings.md)