# Manual de documentación de software

Con el objetivo de consolidar lo aprendido acerca de documentación de software, se ha creado este repositorio como manual de referencia para futuros proyectos.

<br>

# ¿Qué es documentación de software?

La documentación de software es un conjunto de documentos que describen el sistema desde múltiples perspectivas.

Su propósito es facilitar el uso, mantenimiento y desarrollo del software.

Los usuarios pueden usar la documentación para aprender cómo usar el sistema, mientras que los desarrolladores pueden usarla para comprender el diseño o la implementación del sistema.

<br>

# ¿Por qué es importante la documentación de software?

La documentación de software es importante porque:

- **Mejora la calidad del software**: La documentación ayuda a evitar errores, inconsistencias y ambigüedades en las funcionalidades del sistema, así como a facilitar la detección y corrección de defectos.

- **Facilita la comunicación y colaboración**: La documentación permite a los diferentes actores involucrados en el proyecto (clientes, usuarios, devs, testers, etc.) entender los requisitos, funcionalidades y limitaciones del sistema.

- **Reduce el costo y el tiempo de desarrollo**: La documentación ayuda a planificar, organizar y gestionar el proyecto, así como a reutilizar código o componentes existentes. También evita la pérdida de información o conocimiento cuando se produce un cambio de personal o de tecnología.

<br>

# Clasificación de la documentación de software

Existen diferentes tipos de documentación de software. Con el fin de facilitar su comprensión, personalmente los clasifico según tres dimensiones:

- **El elemento documentado:** La primera dimensión se refiere al elemento en sí. Por ejemplo: un requisito, un procedimiento, código, etc.

- **El perfil del lector:** La segunda dimensión corresponde a quién va dirigido el documento. Por ejemplo: desarrolladores, usuarios, analistas, etc.

- **El propósito de la documentación:** La tercera dimensión es el tipo de información que se desea comunicar. Por ejemplo: descripción actual del sistema, especificación de lo que se implementará, etc.

Esto se explica detalladamente [aquí](docs/classification.md).

<br>

# Metadatos de un documento de software

Los metadatos son datos acerca del documento en sí.

Para la documentación de software se recomienda incluir los siguientes metadatos: [Lista de metadatos](docs/meta.md)

<br>

# Niveles de documentación de software

*Más conceptual*

- [Visión (vision)](docs/levels/visions.md): Es la declaración previsora de lo que se espera del proyecto en el futuro.

- [Épica (epic)](docs/levels/epics.md): Es un grupo de funcionalidades o características que responden a una misma necesidad que el sistema debe satisfacer.

- [Característica (feature)](docs/levels/features.md): Es una funcionalidad definida por un conjunto de interacciones.

- [Caso de uso (user story)](docs/levels/use_cases.md): Es la descripción de una interacción con sistema desde la perspectiva del usuario.

- [Implementación (implementation)](docs/levels/implementation.md): Es la descripción técnica de cómo se implementó una funcionalidad.

*Más técnico*

<br>

# Fases de la documentación de software

Las Fases del Desarrollo son los pasos que se siguen al realizar un proyecto de documentación de software.

Estas fases son:

- [Preámbulo](docs/phases/preamble.md): El primer paso del proceso de documentación es conocer la metainformación del trabajo que se debe realizar.

- [Exploración](docs/phases/exploration.md): Durante la exploración debes comprender el contexto del sistema y determinar los procedimientos actuales utilizados por los usuarios.

- [Análisis](docs/phases/analisys.md): El análisis de requerimientos implica identificar las necesidades de los usuarios y los criterios de aceptación para la solución que se proponga.

- [Diseño](docs/phases/design.md): Para el diseño de la solución debes presentar diferentes alternativas como solución a la necesidad y seleccionar la más adecuada.

- [Implementación](docs/phases/implementation.md): Haz seguimiento al desarrollo y agrega textos técnicos acerca de la implementación.

- [Entrega](docs/phases/delivery.md): Agrega detalles, notas y advertencias finales. Entrega la solución creada con la documentación correspondiente.

<br>

# Secciones de un documento de software

_**Abstract**_
- [Página inicial](docs/phases/preamble.md)
- [Prefacio](docs/phases/preamble.md)
- [Glosario](docs/phases/exploration.md)

_**Documentación no técnica** (La documentación no técnica son descripciones e instrucciones claras para un público que puede no estar familiarizado con los detalles del sistema o los procesos.)_

- [Anexos](docs/phases/preamble.md)
- [Reuniones](docs/phases/exploration.md)
- [Procesos](docs/phases/exploration.md)
- [Requerimientos](docs/phases/analisys.md)
- [Casos de uso](docs/phases/design.md)
- [Plan de pruebas](docs/phases/design.md)
- [Notas y advertencias acerca de las decisiones tomadas](docs/phases/design.md)

_**Documentación técnica** (La documentación técnica describe y explica aspectos tecnológicos, características y funciones del software, como su arquitectura, diseño, algoritmos o APIs, con el objetivo de facilitar su comprensión, mantenimiento y colaboración entre desarrolladores.)_

- [Topología](docs/phases/implementation.md)
- [Componentes de software](docs/phases/implementation.md)
- [Diagramas de bases de datos](docs/phases/implementation.md)
- [Especificación de APIs](docs/phases/implementation.md)
- [Algoritmos de servicios](docs/phases/implementation.md)
- [Lista de nuevos permisos](docs/phases/implementation.md)
- [Tareas y actividades](docs/phases/implementation.md)

_**Documentación de entrega** (La documentación de entrega va dirigidada a los usuarios finales del sistema)_

- [Manual de instalación](docs/phases/delivery.md)
- [Manual de uso](docs/phases/delivery.md)
- [Registro de cambios](docs/phases/delivery.md)

<br>

# Apéndices

- [Navegación y estructura](docs/navigation.md)

- [Flujo de trabajo](docs/workflow.md)

- Documentación basada en texto
    - [listas](/docs/text/lists.md)
    - [tablas](/docs/text/tables.md)
    - [código](/docs/text/code.md)