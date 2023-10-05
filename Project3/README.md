<HTML>
<h1>Proyecto 3: Memoria</h1>
Este proyecto contiene el código y la documentación para la construcción de una memoria de acceso aleatorio (RAM) escalable desde 1 bit hasta 64k bits, así como la implementación de un contador de programa (PC)
utilizando componentes digitales. Este proyecto se basa en la construcción y combinación de chips de 1 bit y registros de 16 bits, siguiendo una metodología de diseño de sistemas digitales.

Resumen de la Práctica
En esta práctica, comenzamos construyendo un chip de 1 bit que utiliza el Flip-Flop D (DFF) como elemento básico. Este chip de 1 bit servirá como el bloque de construcción fundamental para nuestro sistema de memoria.
Luego, procedimos a diseñar y ensamblar un registro de 16 bits utilizando 16 chips de 1 bit, como su nombre lo indica. Este registro de 16 bits es esencial para almacenar datos en nuestro sistema de memoria.

Continuando, utilizamos 8 de estos registros de 16 bits para construir la RAM8, una memoria de acceso aleatorio de 8 palabras de 16 bits cada una. Posteriormente, escalamos este enfoque, apilando las RAM8
para crear memorias más grandes: RAM64, RAM512, RAM 4k, RAM 16k y RAM 64k.

Finalmente, utilizando los componentes que hemos construido, implementamos un contador de programa (PC) que controla la secuencia de instrucciones en nuestro sistema digital.
