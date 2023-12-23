# Formalización del desarrollo

La formalización se refiere a convertir la idea de lo que se quiere hacer en documentación.

La formalización se puede dar en múltiples niveles dependiendo de que tan cercano a la implementación sea el documento.

Estos niveles suelen ser:
- Visión (vision)
- Épica (epic)
- Característica (feature)
- Historia de usuario (user story)

# Visión (vision)

Es una declaración previsora de lo que se espera del proyecto más adelante.

La visión generalmente responde a las preguntas:
- ¿A quién atiende el proyecto?
- ¿Cómo se espera que esté el proyecto en 1, 5 o 10 años?
- ¿Qué se hará para lograr esa visión?
- ¿Cuál es la importancia de estos objetivos?

El objetivo de una visión es definir la posición y el propósito a largo plazo del proyecto. Esto permite la alineación de los objetivos y las personas que trabajan en el proyecto hacia un propósito claro.

Una buena visión debe ser:
- **Clara y concisa:** Máximo 3 oraciones que comuniquen claramente la visión del proyecto.
- **Orientada al futuro:** No se trata de como está el proyecto ahora, sino de como se espera que esté.
- **De duración determinada:** Debe tener una fecha determinada en la que se espera que el proyecto alcance sus objetivos.
- **Basada en objetivos:** Debe tener objetivos claros y cuantificables que se desean lograr.
- **Ambiciosa pero realista:** Debe tener un objetivo ambicioso y aun así estar basada en la realidad.
- **Abstracta:** No debe ser una guía completamente documentada, sino más bien una descripción general que le dé al proyecto una dirección estratégica amplia.

# Épica (epic)

Se refiere a un gran volumen de trabajo que sólo es posible completarlo en un período prolongado.

## Tipo de épica

Según la necesidad que se busca satisfacer, las épicas se pueden clasificar en:

- **Nuevo**: Los nuevos sistemas se identifican por su independencia. Si un sistema no requiere la existencia de otros para funcionar, es un desarrollo nuevo. Al crear un proyecto desde cero, se debe solicitar toda la información posible para entender el trasfondo antes de empezar el desarrollo. Al finalizar, se espera la documentación del proyecto en su totalidad.

- **Adición**: Las adiciones son sistemas que dependen de otros para funcionar. Es posible agregar una funcionalidad a un proyecto existente solo con información acerca del módulo que se va a crear. Al finalizar, se espera la documentación del módulo.

- **Reestructuración**: Se le llama reestructuración a la mejora de las características no funcionales de un sistema. Si el sistema hace lo que debe hacer pero es lento o poco intuitivo para el usuario, se realiza una reestructuración que no influye en la funcionalidad esperada sino en las características al rededor de dicha funcionalidad. El esfuerzo para reestructurar un proyecto varía según la cantidad de cambios que se deben realizar, pero parte de un sistema existente, por lo que requiere menos esfuerzo que crear uno desde cero. El conocimiento de partida puede corresponder solo al módulo que se va a reestructurar. Al finalizar, se espera la documentación de los cambios realizados.

- **Corrección**: La corrección se realiza cuando el sistema no funciona correctamente (referente a funcionalidad, no características). El esfuerzo para corregir un proyecto varía según la cantidad de errores que se deben solucionar, pero el proyecto ya existe y la estructura no se modifica, por lo que es el nivel que menos esfuerzo requiere. Inicialmente, se puede conocer sólo el módulo o algoritmo defectuoso y al finalizar, se espera la documentación de las correcciones realizadas.

Esta clasificación indica de manera abstracta el propósito de la Épica e influye en la cantidad de información que se debe solicitar y documentación que se debe entregar. Al entender el tipo de épica, puedes evitar perder tiempo en recopilar información innecesaria o escribir documentos que no aportan valor al proyecto.

# Característica (feature)

Es una característica o funcionalidad específica que un programa o aplicación ofrece.

# Historia de usuario (user story)

Es la especificación de una interacción que los usuarios podrían tener con el sistema.

# Dimensión del desarrollo

Las dimensión del desarrollo hace referencia a qué tantos archivos se deben modificar.

La dimensión se podría clasificar en:
1. Cambios en un sólo archivo
2. Cambios en varios archivos de un sólo directorio
3. Cambios en varios directorios de un sólo sistema
4. Cambios en varios sistemas

# Fases del desarrollo

Las Fases del Desarrollo son los pasos que se deben seguir al realizar el desarrollo del software.

Estas fases son:
- **Preámbulo:** El primer paso del proceso de documentación es conocer la metainformación del trabajo que se debe realizar.

- **Exploración:** Comprende el contexto del sistema y determinar los procedimientos actuales utilizados por los usuarios.

- **Análisis:** Identifica las necesidades de los usuarios y los criterios de aceptación para la solución que se proponga.

- **Diseño:** Presenta diferentes alternativas para solucionar la necesidad y selecciona la más adecuada.

- **Implementación:** Realiza la solución escogida en la fase de diseño.

- **Entrega:** Entrega la solución creada con la documentación correspondiente.