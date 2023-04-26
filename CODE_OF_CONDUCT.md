# Guía de Estilo de Código

Esta guía tiene como objetivo mantener un estilo de código consistente y legible en todo el proyecto.

## Convenciones Generales

- Utiliza TypeScript para todo el código.
- Incluye documentación para cada función, clase o método que escribas cuando el nombre no sea lo suficientemente descriptivo.
- Evitar líneas de código que superen los 90 caracteres
- Usar tipos explícitos siempre que sea posible, en lugar de depender de la inferencia de tipos.
- Evitar el uso de la palabra clave any y en su lugar utilizar tipos más específicos.
- Usar readonly en propiedades que no deben ser modificadas después de la inicializarían.
- Usar el tipo never para las funciones que nunca regresan, como las que lanzan excepciones.
- Evitar el uso de var y en su lugar utilizar let o const.
- Usar el operador === en lugar de == cuando se desee validar igualdad sin conversión.
- Utilizar interfaces para definir formas de objetos en lugar de tipos de objeto explícitos. 

## Convenciones de Nombres

- Usa nombres de variables, funciones y clases descriptivos.
- Usa nombres de clases en PascalCase. Por ejemplo: `NombreDeClase`.
- Usa nombres de variables y funciones en camelCase. Por ejemplo: `nombreDeFuncionOVariable`.
- Usa nombres de constantes  en MAYÚSCULAS separadas por guion bajo.  Por ejemplo: `NOMBRE_DE_CONSTANTE`.


## Indentación

- Usa indentación de 2 espacios.

## Comentarios

- Usa comentarios para explicar el propósito y funcionamiento de tu código cuando el nombre la función, método o clase no sea lo suficientemente descriptivo.
- Usa comentarios en líneas separadas para describir cada sección de código.
- Usa comentarios en línea para explicar fragmentos de código específicos.
- No incluyas comentarios irrelevantes o redundantes.

## Flujo de trabajo de contribución

Sigue estos pasos para contribuir al proyecto:

- Crea un fork del repositorio en GitHub.
- Clona el fork a tu máquina local.
- Crea una nueva rama para trabajar en tu característica o corrección de error.
- Implementa la característica o corrección de error.
- Asegúrate de que todas las pruebas pasen y de que el código siga las convenciones de codificación.
- Haz una solicitud de extracción (PR) a la rama principal del repositorio.
- Espera la revisión y retroalimentación de los colaboradores del proyecto.
- Realiza los cambios solicitados en la retroalimentación si es necesario.
- Una vez que se haya aprobado la solicitud de extracción y se hayan incorporado todos los cambios solicitados, se fusionará la rama de tu PR con la rama principal del repositorio.

## Commits

Utilizamos la convención de mensajes de commit [Conventional Commits](https://www.conventionalcommits.org/) para mantener un registro claro y organizado de los cambios en el proyecto. Aquí están las convenciones de mensaje de commit que debes seguir:

- `FEAT`: Para nuevas funcionalidades.
- `FIX`: Para corrección de errores.
- `DOC`: Para cambios en la documentación.
- `STYLE`: Para cambios que no afectan el comportamiento del código (espacios en blanco, formato, etc.).
- `REFACTOR`: Para cambios en el código que no arreglan errores ni añaden funcionalidades.
- `TEST`: Para agregar pruebas faltantes o corregir pruebas existentes.
- `CHORE`: Para cambios en la configuración, dependencias, etc.


## Licencia

Este proyecto está licenciado bajo la Licencia MIT.
