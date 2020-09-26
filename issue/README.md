Los requisitos de usuario : 5 prácticas esenciales
==================================================

Los requisitos de usuario, ¿Qué son?
------------------------------------

Un **requisito de usuario** es la expresión de una necesidad particular. El requisito de usuario es escrito por el propietario o el usuario del software (ellos saben lo que quieren tener). Sin embargo, el tema está dirigido a los desarrolladores que tendrán que entenderlos para poder hacerlos realidad, y en ese caso hablamos mas bien de [Especificación de Requisitos de Software (ESR)](https://es.wikipedia.org/wiki/Especificación_de_requisitos_de_software). Donde estos ESR deben estar en un documento acordado y redactado por todas las partes (usuarios y desarrolladores), pero esto es otro tema. En este documento nos centraremos en los requisitos de usuario.

Todos los métodos de ingeniería de software requieren resultados claros. El objetivo es que los desarrolladores entiendan las necesidades y creen software que satisfaga a los usuarios.

Especialmente es cuando las necesidades están mal expresadas que los proyectos de software fracasan.
Por lo tanto, debe prestarse especial atención a la redacción de estos requisitos.

Hay diferentes maneras de escribir un requisito dependiendo del método utilizado:

* Los métodos matemáticos o rigurosos requieren que los resultados sean restricciones escritas de manera formal. Esto puede ser, por ejemplo, una fórmula de lógica booleana o incluso una regla matemática.
* Los métodos de modelización como el UML ofrecen lenguajes adecuados para escribir los requisitos de usuario. En el UML, podemos, por ejemplo, utilizar diagramas de casos de uso.
* Los métodos ágiles requieren que los requisitos se escriban en lenguaje natural en forma de una [Historia de Usuario](https://es.wikipedia.org/wiki/Historias_de_usuario). La escritura de un escenario puede seguir una plantilla predefinida ("Como (rol) quiero (algo) para poder (beneficio)").
* etc.

Si la redacción de los requisitos es importante, también lo es su gestión. La gestión de un requisito permite seguir su evolución a lo largo del tiempo. Un requisito generalmente pasa por varias etapas:

* en proceso de redacción, cuando el resultado aún no está completamente redactado.
* escrito y en espera de evaluación, donde el resultado está escrito pero no ha sido evaluado. La evaluación permite especificar el tipo de requisito: ¿si es la solicitud de una nueva característica? ¿una evolución de una característica existente? ¿una corrección de errores? ¿una optimización del rendimiento? etc.
* evaluado y en espera de la planificación, cuando el requisito se valida pero aún no se haya planificado. La planificación permite colocar el resultado en una hoja de ruta y así saber cuándo se realizará.
* planificado, entonces sabemos cuándo se alcanzará el resultado.
* que se pueda probar. cuando el requisito tiene una [prueba](../test) que permitirá, una vez realizado el requisito, verificar su realización.
* en curso de realización, cuando las tareas que permiten realizar el requisito han comenzado.
* realizado, cuando se hayan realizado todas las tareas necesarias para completar el requisito.
* probado, cuando el requisito se alcanza y se prueba. En principio, el requisito se considera probado cuando se ha superado la prueba (positivo).
* entregado o desplegado, cuando el requisito es accesible para los usuarios. Cuando se ha integrado en un [lanzamiento (release)](../release)

¿Qué es la calidad de los requisitos?
-------------------------------------

La calidad del software depende en gran medida de la calidad de los requisitos. Si los requisitos no son de buena calidad, hay más de un 80% de posibilidades de que el proyecto no tenga éxito.

La calidad del requisito se refleja en la redacción y en el seguimiento. En efecto, los requisitos deben estar perfectamente escritos, pero también su gestión debe ser precisa.

Lista de buenas prácticas:
----------------------------

### Redacción

* [identificar de manera única los requisitos](./identifier.md)
* [aclarar o precisar los requisitos](./preciser.md)
* [homogeneizar los requisitos](./homogeneiser.md)

### Gestión de modificaciones

* [calificar el tipo de requisitos, su importancia y dificultad](./qualifier.md)
* [planear los requisitos a lo largo del tiempo](./planifier.md)
* [cerrar un requisito](./fermer.md)
