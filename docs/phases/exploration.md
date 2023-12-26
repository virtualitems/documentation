[volver al inicio](/readme.md)

# Fase de exploración en la documentación

Durante la fase de exploración debes **comprender el contexto del sistema** y determinar los **procedimientos actuales** utilizados por los usuarios.

## Contexto del desarrollo

El contexto es el marco conceptual del sistema y proporciona información esencial para establecer un lenguaje común entre todas las partes involucradas en el proyecto. Por ejemplo, en un sistema de inventario, un producto es un objeto tangible, mientras que en un sistema de ventas, un producto puede ser un servicio intangible.

## Lenguaje ubicuo

Al abordar un nuevo desarrollo debes tener en cuenta que todos los involucrados hacen parte de un mismo equipo y por lo tanto deben entenderse con un lenguaje común, a esto se le conoce como Lenguaje Ubicuo. El objetivo es evitar perder o malinterpretar conocimiento a la hora de documentar el sistema.

Este lenguaje común pactado debe usarse tanto en la comunicación como en el código para facilitar la comprensión del sistema en el tiempo. De esta manera, el código transmite los conceptos del negocio y se utilizan tanto en el debate del diseño como en la implementación de las funcionalidades del proyecto.

Debes tener en cuenta que al estar vinculados el desarrollo y el lenguaje, un cambio en el lenguaje supone un cambio en el sistema. Por lo tanto, cualquier posible confusión en la terminología debe ser resuelta entre los integrantes del equipo.

### Glosario

Es una lista de términos o conceptos que podrían ser difíciles, confusos o desconocidos.

La definición asociada a cada término debe ser lo más simple posible y puede incluir una lista de términos alternativos. Debes dejar constancia de por qué son menos adecuados que los consensuados.

## Reuniones

Toda reunión debe tener una agenda previa y un acta de reunión posterior. La agenda debe incluir los temas a tratar y los participantes. El acta debe incluir los temas tratados, las decisiones tomadas y los responsables de cada tarea.

## Procesos

Durante la fase de exploración, lo más importante es comprender los procesos actuales que realizan los usuarios. Es decir, se debe responder a la pregunta ¿cómo se hace actualmente?

Para esto, debes usar técnicas de observación y recolección de información, por ejemplo entrevistas.

Ten en cuenta que los usuarios pueden no ser conscientes de sus propios procesos, por lo que debes estar atento a los detalles.

Los procesos de pueden catalogar en 3 tipos:

- **Procesos principales**: Son los procesos donde todo funciona correctamente.

> Por ejemplo: al intentar iniciar sesión, mi nombre de usuario y contraseña son correctos y puedo acceder al sistema.

- **Procesos de excepción**: Son los procesos que se realizan cuando algo no funciona correctamente pero se logra cumplir el objetivo principal.

> Por ejemplo: al intentar iniciar sesión, mi nombre de usuario es correcto pero mi contraseña es incorrecta, por lo que puedo recuperar mi contraseña y después acceder al sistema.

- **Procesos alternativos**: Son los procesos donde fallas graves impiden cumplir el objetivo principal.

> Por ejemplo: al intentar iniciar sesión, mi nombre de usuario no existe por lo que no puedo acceder al sistema.