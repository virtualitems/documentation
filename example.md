Dimensión del desarrollo

Nuevo X.0.0
    Nuevo (adición) -.X.0
    Nuevo (reestructuración) -.X.0
    Nuevo (corrección) -.0.X

Adición 1.X.1
Reestructuración 1.X.1

Corrección 1.1.X

----------------------------------------

Documentación de desarrollo

Documentación para el equipo de sistemas acerca de la implementación realizada con el propósito de entender el contexto y funcionamiento del sistema.

----------------------------------------

Prefacio

Los paréntesis indican qué sección debes tener en cuenta según la dimensión del desarrollo que estés construyendo. Algunas secciones no serán necesarias, en ese caso la sección se dejará como hoja en blanco.

Explica en una frase o máximo en un párrafo máximo de 100 palabras de qué se trata el desarrollo.

----------------------------------------

Glosario

Lista términos clave o conceptos que podrían ser confusos o desconocidos.

----------------------------------------

Documentación no técnica

(hoja intencionalmente en blanco)

La documentación no técnica son descripciones e instrucciones claras para un público que puede no estar familiarizado con los detalles del sistema o los procesos.

----------------------------------------

Anexos

Esta sección hace parte de la fase de exploración y entendimiento del contexto.

Agrega enlaces a pliegos, documentos, imágenes, videos, audios u otros elementos provistos para el desarrollo.

----------------------------------------

Reuniones

Esta sección hace parte de la fase de exploración y entendimiento del contexto. Escribe notas y aclaraciones según lo dialogado en las reuniones.

Agrega enlaces a las reuniones grabadas.

Lista las preguntas realizadas en las reuniones y sus respuestas.

----------------------------------------

Procesos

Esta sección hace parte de la fase de exploración y entendimiento del contexto. Explica sin tecnicismos los procesos vigentes y cómo se están realizando.

El objetivo es ENTENDER los procesos vigentes, NO las necesidades ni proponer soluciones.
Agrega enlaces a diagramas de flujo o BPMN que describen los procesos. En caso de ser un desarrollo de corrección, el proceso es el paso a paso del error.

----------------------------------------

Requerimientos

Esta sección hace parte de la fase de análisis de las necesidades. Escribe notas no técnicas y advertencias acerca de los requerimientos. Agrega el enlace al documento de levantamiento de requerimientos o haz un listado de lo requerido en el sistema.

Escribe los requerimientos como Historias de Usuario: El <rol> requiere <necesidad> con el propósito de <finalidad>. La necesidad siempre debe estar escrita en infinitivo (verbo finalizado en ar, er o ir)

----------------------------------------

Casos de uso

Objetivo: identificador que debe empezar con un verbo en infinitivo.

Precondiciones: Lista de condiciones necesarias para poder ejecutar el procedimiento.

Postcondiciones: Lista de efectos resultantes después de llevar a cabo el procedimiento.

Flujos alternos: Lista de condiciones que conllevan a Excepciones o Errores.

Permisos: Lista de permisos que debe tener el usuario para ejecutar el caso de uso.

Esta sección hace parte de la fase de diseño de la solución. Escribe una especificación por cada caso de uso. Cada especificación debe estar en una página diferente.

No es necesario copiar los textos de ayuda por cada especificación.

----------------------------------------

Pruebas

Esta sección hace parte de la fase de diseño de la solución. Agrega el enlace al documento de diseño de pruebas para cada servicio.

----------------------------------------

Notas y advertencias acerca de las decisiones tomadas

Esta sección hace parte de la fase de diseño de la solución. Describe las razones y advertencias de las decisiones realizadas.

----------------------------------------

Documentación técnica

(hoja intencionalmente en blanco)

La documentación técnica describe y explica aspectos tecnológicos, características y funciones del software, como su arquitectura, diseño, algoritmos o APIs, con el objetivo de facilitar su comprensión, mantenimiento y colaboración entre desarrolladores.

----------------------------------------

Topología

Esta sección hace parte de la fase de diseño de la solución. Escribe notas técnicas y advertencias acerca de la infraestructura sobre la que se construye el sistema. Agrega el enlace al diagrama de despliegue.

Escribe las especificaciones para los static files o los media files de ser necesario.

----------------------------------------

Componentes de software

Esta sección hace parte de la fase de diseño de la solución. Escribe notas técnicas y advertencias acerca de las aplicaciones Django creadas.

----------------------------------------

Diagramas de bases de datos

Esta sección hace parte de la fase de diseño de la solución. Escribe notas técnicas y advertencias acerca de las bases de datos del sistema. Agrega el enlace al diagrama de la base de datos.

----------------------------------------

Especificación de APIs

Esta sección hace parte de la fase de diseño de la solución. Escribe notas técnicas y advertencias acerca de las APIs. Agrega el enlace al documento de especificación de APIs.

Recuerda que una API es la forma de consumir un servicio que puede ser a través de HTTP o las funciones públicas de un módulo.

----------------------------------------

Algoritmos de servicios

Esta sección hace parte de la fase de diseño de la solución. Haz una descripción técnica del algoritmo usado para cada servicio. Puedes usar listas numeradas para describir un paso a paso o puedes usar diagramas técnicos.

----------------------------------------

Lista de permisos creados

Esta sección hace parte de la fase de diseño de la solución. Agrega el enlace al listado de los permisos de los usuarios.

----------------------------------------

Tareas y actividades

Esta sección hace parte de la fase de seguimiento. Agrega el enlace a la rama en Gitlab.

Recuerda agregar docstrings en el código.

----------------------------------------

Manual de instalación

Esta sección hace parte de la fase de entrega. Agrega notas y advertencias que se deben tener en cuenta durante el proceso de despliegue.

Lista las dependencias que requiere el sistema en su instalación, configuración o funcionamiento de ser necesario.

Explica cómo instalar el sistema de ser necesario.

Explica cómo configurar el sistema instalado o agrega los comandos que se deben ejecutar en consola para la configuración.

----------------------------------------

Manual de uso

Esta sección hace parte de la fase de entrega. Agrega el enlace al manual de uso para el usuario final.

Si es necesario, agrega al manual un apéndice de errores comunes y cómo evitarlos o solucionarlos.
Por ejemplo: si en un cargue masivo, el CSV debe estar separado por tabs y no por comas.

----------------------------------------

Errores presentados a causa del desarrollo implementado

Esta sección hace parte de la fase de mantenimiento del sistema. Describe errores que ocurrieron a causa del desarrollo implementado para posterior análisis y corrección.

Recuerda que el desarrollo implementado debe ser la causa del error, no el componente afectado.

----------------------------------------

Configuración de texto

peligro
advertencia
información
éxito

texto normal
texto bold
texto italic
texto código

título
subtítulo
encabezado 1
encabezado 2
encabezado 3
