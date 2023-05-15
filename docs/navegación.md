# Navegación y estructura de la documentación de un proyecto de software

La navegación es la forma en que el lector puede moverse a través del contenido del documento. Una buena navegación permite que el lector encuentre fácilmente la información que necesita.

La navegación también puede incluir la forma en que se organizan y etiquetan las secciones del documento. Por ejemplo, se pueden utilizar encabezados descriptivos y jerarquizados para que el lector pueda entender rápidamente la estructura del documento y localizar la información específica que está buscando.

Cada proyecto de documentación de software cuenta con dos secciones: documentación técnica y documentación no técnica.

<br/>


# Estructura propuesta

La estructura propuesta para la documentación es la siguiente:

```
├── Documentación no técnica
│   ├── Resumen ejecutivo
│   ├── Glosario
│   ├── Referencias
│   └── Descripción general
│       ├── Contexto
│       ├── Usuarios
│       ├── Necesidades
│       └── Funcionalidades
|
└── Documentación técnica
    ├── Despliegue
    ├── Arquitectura
    ├── Módulos
    ├── Datos
    ├── Seguridad
    └── Change log
```

<br/>


# Documentación no técnica

Corresponde usualmente a la primera mitad del documento. Esta sección está dirigida a directivos, analistas, usuarios o perfiles ajenos al desarrollo de software. Por lo tanto, debe ser fácil de leer y entender. Esta sección incluye:

<br/>


## Resumen ejecutivo

Esta sección es la primera que el lector encontrará en el documento, debe ser atractiva y concisa.

Nuestros lectores son personas ocupadas que no necesariamente leerán toda la documentación. Por lo tanto, el documento debe responder a las preguntas esenciales desde los primeros párrafos.

El resumen ejecutivo debe ofrecer una descripción completa del sistema, así como su propósito, alcance y funciones principales para que el lector pueda comprenderlo sin necesidad de leer el documento completo.

<br/>


## Glosario

El glosario debe contener definiciones, acrónimos y abreviaturas que se utilizan en el documento y pueden ser confusas o desconocidas para el lector. Estos términos deben estar ordenados alfabéticamente.

<br/>


## Referencias

Las referencias son enlaces a otros documentos que pueden ser de interés para el lector y complementan la información del documento.

<br/>


## Descripción general

En esta sección se encuentra toda la información detallada del proyecto desde una perspectiva no técnica. Esta sección incluye:

<br/>


### Contexto

Esta sección describe el contexto en el que se desarrolla el proyecto.

[ver más](fases/exploraci%C3%B3n.md)

<br/>


### Usuarios

En esta sección se describe detalladamente el perfil de los usuarios del sistema.

<br/>


### Necesidades

Esta sección describe las necesidades que el sistema debe satisfacer.

[ver más](fases/an%C3%A1lisis.md)

<br/>


### Funcionalidades

Esta sección describe las funcionalidades que el sistema ofrece para satisfacer las necesidades de los usuarios.

[ver más](fases/dise%C3%B1o.md)

<br/>


# Documentación técnica

Corresponde usualmente a la segunda mitad del documento. Esta sección está dirigida al equipo técnico de ingeniería de software. Esta sección debe ser precisa y detallada. Se recomienda incluír diagramas, visualizaciónes o ejemplos que faciliten la comprensión. Esta sección incluye:

<br/>


## Despliegue

Esta sección incluye información acerca de las dependencias del sistema, su instalación y configuración.

<br/>


## Arquitectura

Esta sección contiene información acerca de la arquitectura del sistema:
- Estructura de directorios
- Capas del software
- Componentes y sus relaciones
- Cíclo de vida
- Topología

<br/>


### Módulos

Esta sección contiene información acerca de los módulos del sistema.

<br/>


### Almacenamiento de datos

Esta sección contiene información acerca de la forma en que se persisten los datos y la estructura de la base de datos.

<br/>


### Ejecuciones en tiempo real

Esta sección contiene información acerca de actividades del sistema que se ejecutan en tiempo real. Por ejemplo: cron jobs, eventos, web sockets, etc.

<br/>


## Seguridad

Esta sección contiene información acerca de los mecanismos o controles de seguridad del sistema. Por ejemplo: autenticación, autorización, encriptación, hashing, etc.

<br/>


## Change log

Esta sección contiene información acerca de los cambios realizados en cada versión del sistema. Debe contener toda la información acerca del continúo desarrollo del sistema.
