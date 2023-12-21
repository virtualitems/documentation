# Documentación de código

Existen dos formas de documentar código:


<br/>

## En el código fuente

Al documentar en el código fuente, debes usar la sintaxis de comentarios del lenguaje de programación que estés usando.

Estos comentarios pueden ser de **una sola línea**, para agregar anotaciones, o de **varias líneas**, para explicar un bloque de código.

Ejemplo usando JavaScript:

```javascript
/**
 * @description Función que calcula la mayor de dos edades.
 * @param {number} age1 Edad de la primer persona
 * @param {number} age2 Edad de la segunda persona
 *
 * @returns {number} La edad mayor
 *
 * @throws {Error} Si alguna de las edades es negativa
 */
function compareAges(age1, age2) {

    if (age1 < 0 || age2 < 0) {
        // las edades no pueden ser negativas
        throw new Error('Edad no válida');
    }

    return age2 > age1 ? age2 : age1;  // si son iguales, siempre devuelve el primero
}
```

Los comentarios de una sola línea ( // ) NO tienen standard así que se pueden usar de la forma que sea más conveniente.

Los comentarios de varias líneas ( /* */ ) SÍ tienen reglas de documentación pero varía según el lenguaje de programación y cada lenguaje suele tener múltiples standard acerca de cómo escribirlos. Por ejemplo, en JavaScript se puede usar JsDoc, en Python se puede usar Sphinx, en Java se puede usar JavaDoc, etc.

No obstante, aunque la sintaxis varíe, los comentarios de varias líneas suelen incluir:

<br/>

- **Para clases:**
    - Una descripción general de la clase.
    - Una descripción de la herencia de la clase.
    - Una descripción de los atributos de la clase.

<br/>

- **Para funciones y métodos:**
    - Una descripción general del código.
    - Una descripción de los datos de entrada y de salida.
    - Una descripción de los errores que puede lanzar el código.

<br/>

## En un documento aparte

Cuando se usa un documento externo para describir el código, se escribe generalmente en Markdown ya que es un formato sencillo y fácil de leer.

Este tipo de documentación es más extenso pudiendo profundizar en diferentes aspectos del código.

Las secciones más comunes son:

- **Metainformación:** Información sobre el documento como título, fecha, autor, etc.

- **Descripción:** Descripción del código y su propósito.

- **Instalación:** Especificación de dependencias e instrucciones para instalar el componente y configurar el entorno de ejecución.

- **Uso:** Ejemplos de casos de uso. Los programadores utilizan ejemplos para asimilar rápidamente en el uso del código por lo que casi siempre navegan primero por los ejemplos exhibidos antes de leer un tema en su totalidad. Debido a su especial consideración, el código de muestra requiere mucha atención. Un código de muestra claro y detallado es frecuentemente la mejor documentación. Los casos de uso suelen contener Título, Descripción, Ejemplo y Excepciones.

- **Advertencias:** Precauciones que se deben tener en cuenta al usar el código.

- **Referencias:** Enlaces a otros documentos que puedan ser útiles para entender el código.
