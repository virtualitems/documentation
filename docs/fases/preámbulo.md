# Preámbulo al desarrollo

El primer paso del proceso de documentación es conocer la metainformación del trabajo que se debe realizar.

A continuación se presentan la metainformación sugerida para la documentación en desarrollo de software.

<br/>


## Prioridad

La prioridad indica la importancia del trabajo a realizar e influye en el orden en que se realizan las tareas.
La medida depende del equipo que realice el trabajo.

<br/>


## Tipo de desarrollo según la dificultad

Esta clasificación indica de manera abstracta el esfuerzo que se debe invertir en el desarrollo e influye en la cantidad de información que se debe solicitar y documentación que se debe entregar.

Al entender el tipo de desarrollo, puedes evitar perder tiempo en recopilar información innecesaria o escribir documentos que no aportan valor al proyecto.

<br/>

Las categorías ordenadas de mayor a menor son:

- **Nuevo**: Los nuevos sistemas se identifican por su independencia. Si un sistema no requiere la existencia de otros para funcionar, es un desarrollo nuevo. Al crear un proyecto desde cero, se debe solicitar toda la información posible para entender el trasfondo antes de empezar el desarrollo. Al finalizar, se espera la documentación del proyecto en su totalidad.

- **Adición**: Las adiciones son sistemas que dependen de otros para funcionar. Es posible agregar una funcionalidad a un proyecto existente solo con información acerca del módulo que se va a crear. Al finalizar, se espera la documentación del módulo.

- **Reestructuración**: Se le llama reestructuración a la mejora de las características no funcionales de un sistema. Si el sistema hace lo que debe hacer pero es lento o poco intuitivo para el usuario, se realiza una reestructuración que no influye en la funcionalidad esperada sino en las características al rededor de dicha funcionalidad. El esfuerzo para reestructurar un proyecto varía según la cantidad de cambios que se deben realizar, pero parte de un sistema existente, por lo que requiere menos esfuerzo que crear uno desde cero. El conocimiento de partida puede corresponder solo al módulo que se va a reestructurar. Al finalizar, se espera la documentación de los cambios realizados.

- **Corrección**: La corrección se realiza cuando el sistema no funciona correctamente (referente a funcionalidad, no características). El esfuerzo para corregir un proyecto varía según la cantidad de errores que se deben solucionar, pero el proyecto ya existe y la estructura no se modifica, por lo que es el nivel que menos esfuerzo requiere. Inicialmente, se puede conocer sólo el módulo o algoritmo defectuoso y al finalizar, se espera la documentación de las correcciones realizadas.
