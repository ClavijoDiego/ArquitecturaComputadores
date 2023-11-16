<HTML>
  <h1> Ensamblador</h1>

El ensamblador juega un papel crucial en el desarrollo de software de sistemas informáticos. Su función principal es traducir programas escritos en un lenguaje de bajo nivel, como ensamblador,
a código de máquina que pueda ser ejecutado directamente por la computadora. A continuación se detallan algunas razones por las que el ensamblador es importante y para qué se utiliza:

<h4> Traducir a código de máquina:</h3>
El ensamblador traduce programas escritos en lenguaje ensamblador a código de máquina. El código de máquina es una representación binaria de instrucciones que la CPU puede ejecutar directamente.

<h4> Interacción con la arquitectura informática:</h4>
Assembler permite a los programadores interactuar directamente con la arquitectura de la computadora. Puede utilizar las instrucciones especiales de la CPU y acceder directamente a registros y direcciones de memoria.

<h4>Eficiencia y gestión de recursos:</h4>
La programación en ensamblador brinda a los desarrolladores un control más detallado sobre los recursos del sistema, como los registros y la memoria. Esto permite una programación más eficiente optimizada para tareas específicas.

<h4>Programación de sistemas embebidos:</h4>
En sistemas integrados y en tiempo real donde los recursos son limitados y la eficiencia es crítica, el ensamblador se utiliza a menudo para programar dispositivos específicos.

<h4>Desarrollo de sistemas operativos:</h4>
El ensamblador es fundamental en el desarrollo de sistemas operativos. Las partes críticas del sistema operativo a menudo se implementan en lenguaje ensamblador para un rendimiento óptimo y un control preciso del hardware.

<h4>Herramientas de traducción y desarrollo:</h4>
Los compiladores generan código de máquina a partir de lenguajes de alto nivel y los ensambladores son una parte integral de este proceso. Además, las herramientas de desarrollo como los depuradores y los analizadores de rendimiento pueden utilizar la información generada por el ensamblador.

<h2>Componentes:</h2>

<h4>Clase Assembler:</h4>

La clase "Assembler" es responsable de traducir programas escritos en el Lenguaje de Ensamblaje Hack a código de máquina.
Utiliza un Analizador para iterar a través del código de ensamblaje, una clase de Código para codificar instrucciones y una Tabla de Símbolos para gestionar símbolos.

<h4>Clase Code:</h4>
La clase de "Code" proporciona asignaciones para varios mnemónicos a sus representaciones binarias.
Maneja el formato de instrucciones A e instrucciones C.

<h4>Clase Parser:</h4>
La clase "Parser" lee y analiza programas escritos en el Lenguaje de Ensamblaje Hack desde un archivo fuente.
Filtra comentarios y líneas vacías y maneja diferentes tipos de comandos (A-command, C-command y L-command).

<h4> Clase SymbolTable:</h4>
La clase SymbolTable administra las direcciones vinculadas a los símbolos en el código de ensamblaje. Sus tareas incluyen inicializar la tabla con valores predeterminados y direcciones iniciales, agregar pares de símbolos y direcciones, verificar la existencia de un símbolo, recuperar la dirección asociada a un símbolo y aumentar las direcciones de programa y datos según sea necesario.

<h4> Clase Program:</h4>
La clase Program funciona como el punto de inicio para la ejecución del ensamblador. Sus tareas principales incluyen verificar la existencia y validez del archivo fuente, determinar la ruta y nombre del archivo de salida (.hack), iniciar el temporizador para medir el tiempo de traducción, crear una instancia del Ensamblador para la traducción y manejar posibles errores de entrada/salida, mostrando mensajes informativos sobre el proceso y su duración.

<h4> Clase CommandType:</h4>
La enumeración CommandType define los tipos de comandos en el Lenguaje de Ensamblaje Hack. Sus valores (A_COMMAND, C_COMMAND y L_COMMAND) permiten clasificar los comandos durante el análisis del código fuente.

</HTML>
