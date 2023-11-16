El ensamblador juega un papel crucial en el desarrollo de software de sistemas informáticos. Su función principal es traducir programas escritos en un lenguaje de bajo nivel, como ensamblador,
a código de máquina que pueda ser ejecutado directamente por la computadora. A continuación se detallan algunas razones por las que el ensamblador es importante y para qué se utiliza:

Traducir a código de máquina:
El ensamblador traduce programas escritos en lenguaje ensamblador a código de máquina. El código de máquina es una representación binaria de instrucciones que la CPU puede ejecutar directamente.

Interacción con la arquitectura informática:
Assembler permite a los programadores interactuar directamente con la arquitectura de la computadora. Puede utilizar las instrucciones especiales de la CPU y acceder directamente a registros y direcciones de memoria.

Eficiencia y gestión de recursos:
La programación en ensamblador brinda a los desarrolladores un control más detallado sobre los recursos del sistema, como los registros y la memoria. Esto permite una programación más eficiente optimizada para tareas específicas.

Programación de sistemas embebidos:
En sistemas integrados y en tiempo real donde los recursos son limitados y la eficiencia es crítica, el ensamblador se utiliza a menudo para programar dispositivos específicos.

Desarrollo de sistemas operativos:
El ensamblador es fundamental en el desarrollo de sistemas operativos. Las partes críticas del sistema operativo a menudo se implementan en lenguaje ensamblador para un rendimiento óptimo y un control preciso del hardware.

Herramientas de traducción y desarrollo:
Los compiladores generan código de máquina a partir de lenguajes de alto nivel y los ensambladores son una parte integral de este proceso. Además, las herramientas de desarrollo como los depuradores y los analizadores de rendimiento pueden utilizar la información generada por el ensamblador.

Componentes:
Clase Assambler:

La clase "Assembler" es responsable de traducir programas escritos en el Lenguaje de Ensamblaje Hack a código de máquina.
Utiliza un Analizador para iterar a través del código de ensamblaje, una clase de Código para codificar instrucciones y una Tabla de Símbolos para gestionar símbolos.
Clase Code:

La clase de "Code" proporciona asignaciones para varios mnemónicos a sus representaciones binarias.
Maneja el formato de instrucciones A e instrucciones C.
Clase Parser:

La clase "Parser" lee y analiza programas escritos en el Lenguaje de Ensamblaje Hack desde un archivo fuente.
Filtra comentarios y líneas vacías y maneja diferentes tipos de comandos (A-command, C-command y L-command).
