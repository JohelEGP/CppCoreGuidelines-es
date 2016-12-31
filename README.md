#[Pautas centrales de C++](http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines)

>«Dentro de C++ hay un lenguaje más pequeño, simple y seguro contendiendo por salir.»
>-- <cite>Bjarne Stroustrup</cite>

Las [pautas centrales de C++](CppCoreGuidelines.md) son un esfuerzo colaborativo dirigido por Bjarne Stroustrup, similar al mismo lenguaje C++. Son el resultado de muchas discusiones y diseños por muchas personas a través de un número de organizaciones. Su diseño promueve la aplicabilidad y adopción general, pero su organización tiene la libertad de copiarlas y modificarlas para adaptarlas a sus necesidades.

## Iniciándose

Las pautas se encuentran en [CppCoreGuidelines](CppCoreGuidelines.md). También hay [una versión formateada para navegación] (http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines) que se integra manualmente y por tanto es un poco más antigua que la versión en la rama master.

Muchas de las pautas utilizan la biblioteca de apoyo a las pautas. Una implementación está disponible en [GSL: Guideline Support Library](https://github.com/Microsoft/GSL).

## Fondo y alcance

El objetivo de las pautas es ayudar a las personas a usar C++ moderno efectivamente. Por «C++ moderno» nos referimos a C++11 y C++14 (y pronto C++17). En otras palabras, ¿cómo le gustaría que se viera su código dentro de 5 años, dado que puede comenzar ahora? ¿Y a los 10 años?

Las pautas se concentran en cuestiones de relativamente alto nivel, como interfaces, administración de recursos, administración de memoria, y concurrencia. Tales reglas afectan la arquitectura de las aplicaciones y el diseño de bibliotecas. Seguir las reglas guiará a código que es seguro de tipo estáticamente, no fuga recursos, y atrapa mucho más errores de programación lógicos que el código común de hoy. Y correrá rápido -- puede costearse hacer las cosas bien.

Nos preocupamos menos por las cuestiones de bajo nivel, como las convenciones de nombramiento y el estilo de sangría. Sin embargo, ningún tema que pueda ayudar a un programador está fuera de alcance.

Nuestro set de reglas inicial enfatizan la seguridad (de varias formas) y simplicidad. Muy bien puede que sean demasiado estrictas. Esperamos tener que introducir más excepciones para acomodar mejor las necesidades del mundo real. También necesitamos más reglas.

Encontrará que algunas de las reglas contradicen sus expectativas o incluso su experiencia. ¡Si no hemos sugerido que cambie su manera de codificar de alguna manera, hemos fallado! ¡Por favor, intente verificar o refutar reglas! En particular, realmente nos gustaría que se respalden algunas de nuestras reglas con mediciones o mejores ejemplos.

Encontrará algunas de las reglas obvias o incluso triviales. Por favor, recuerde que el propósito de la pauta es ayudar a alguien menos experimentado o con un antecedente o lenguaje diferente para ponerse al día.

Las reglas están diseñadas para ser respaldadas por herramientas de análisis. La violación de reglas serán marcadas con referencias (o vínculos) a la regla relevante. No esperamos que memorice todas las reglas antes de intentar escribir código.

Se pretende que las reglas sean introducidas gradualmente en una base de código. Planeamos construir herramientas para eso y esperamos que otros también.

## Contribuciones y licencia

Se aprecian mucho los comentarios y sugerencias sobre mejoras. Planeamos modificar y extender este documento a medida que mejore nuestro entendimiento, el lenguaje y el set de bibliotecas disponible. Más detalles disponibles en [CONTRIBUTING](./CONTRIBUTING.md) y [LICENSE](./LICENSE).
