Los niveles de abstraccion simplifican el trabajar con sistemas complejos organizandolos en diversas capas donde cada capa ofrece un tipo de vista en concreto.
**En los niveles altos**, se aprecia la funcionalidad de manera general y facil de entender. Mientras que **en los niveles bajos**, se trabaja directamente con el hardware o detalles mas tecnicos%% o complicados si se quiere tambien %%

## Los Distintos Tipos de Niveles
#### Nivel 6 : Usuario - Aplicaciones
Siendo este el nivel mas alto, es donde **el usuario interactúa de manera directa con las aplicaciones (o sistemas distribuidos)** que se muestran en pantalla. Por ejemplo : videojuegos, navegadores web, etc.

#### Nivel 5 : Lenguajes de Alto Nivel
Este nivel hace referencia a **lenguajes de programacion** como lo son **Java, Python, C++,etc**. Estos se apoyan en compiladores o interpretes que traducen el codigo a un nivel mas entendible para la maquina.

#### Nivel 4 : Lenguaje Ensamblador
Son instrucciones mas directas que estan conectadas "mas de cerca" con el hardware. Cada linea de codigo **Assembley** corresponde a una instrucción en binario que el procesador puede entender. Dicho de otra manera "*cada instruccion se mapea directamente a una instruccion de maquina especifica del procesador*"

#### Nivel 3 : Sistema Operativo
En este nivel el sistema operativo se comunica directamente con el hardware a traves de [[Controladores de Dispositivos|controladores de dispositivos]], dependiendo todavia de niveles mas bajos para ejecutar comandos especificos en el procesador

#### Nivel 2 : ISA (Instruction Set Architecture) - Conjunto de Instrucciones
Es el nivel que define cuales instrucciones pueden ser ejecutadas. Esta capa sirve como puente entre el hardware **(microarquitectura)** y el software. **Cada procesador tiene su ISA**

#### Nivel 1 : Microarquitectura
Define la implementacion fisica del ISA, aquí se especifica como el procesador ejecuta las instrucciones, gestionando elementos como [[Registros|registros]], [[Arithmetic Logic Unit - ALU|ALU]], [[Unidad de Control|unidad de control]] y la [[Memoria Caché|memoria caché]]
%% Incluye tecnicas como pipeline %%

#### Nivel 0 : Logica Digital
La logica digital se encarga de transformar las señales electricas en ceros y unos, los cuales representan al [[Sistema Binario|sistema binario]]. Esta compuesta por **transistores** que forman [[Compuertas Logicas|compuertas logicas]]**(AND, OR, NOT, XOR, etc)**