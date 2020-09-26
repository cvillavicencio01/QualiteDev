Identificar de manera única los requisitos
==========================================

Los requisitos deben ser identificados de manera única. Cada requisitos debe tener un identificador único en su proyecto.

Este identificador permite distinguir el requisito de cualquier otro, independientemente de su estado.

Si los requisitos no tienen un identificador, se pueden mezclar con otros. Esto da lugar a un control deficiente de la gestión de las requisitos. En el peor de los casos, podemos olvidarnos de los requisitos y, por lo tanto, no crear un software que corresponda a la necesidad expresada.

Objetivo
--------

Esta práctica es muy simple de implementar. Todo lo que tienes que hacer es dar un identificador único a cada requisito.

La forma más fácil es asignar un número a cada requisito. Este número puede construirse de forma incremental (empezando por el número 1 y añadiendo 1 a cada nuevo requisito).

No es aconsejable dar una semántica al identificador, por ejemplo para dar significado al requisito. Algunos proyectos utilizan prefijos como identificadores para agruparlos. A largo plazo, esto es contraproducente. Es mejor mantener un único objetivo que es identificar los requisitos de manera única en el proyecto.

Control
--------

Para controlar esta práctica, simplemente hay que recorrer todos los requisitos y comprobar que cada uno de ellos tiene un identificador único. Así se podrá comprobar que esta práctica es respetada.

Incluso se puede plantear qué mecanismo se puede utilizar para encontrar un nuevo identificador.
