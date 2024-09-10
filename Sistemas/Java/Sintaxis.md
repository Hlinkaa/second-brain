---
Lenguaje: Java
Fecha: 10/09/2024
Fuente: Pensando la Computación como un Científico
tags:
  - Java
  - SIntaxis-Java
---

- el **<font color ="magenta">NOMBRE DEL ARCHIVO</font>** debe ser **<font color ="magenta">IDENTICO</font>** al **<font color = "magenta">NOMBRE DE LA CLASE</font>**
- la mayoría de las veces, cada clase esta en un archivo separado con una extensión <font color = "magenta">.JAVA</font>. Los archivos de clase generalmente se agrupan en carpetas denominadas <font color ="magenta">PAQUETES</font>
- Java es <font color ="magenta">CASE SENSITIVE</font>, esto quiere decir que <font color ="magenta">distingue de mayusculas y minusculas</font>. *String != string*.
- El comienzo del procesamiento del programa Java **SIEMPRE** empieza en el método principal : %% Apple Case = primera letra en mayúscula %%
 
```java
public static void main (String[] args)
```


> [!NOTE] Importante
> El método *main()* es una parte requerida de **cualquier programa de Java**

- Metodo es una secuencia de comandos. Los metodos definen el <font color ="magenta">COMPORTAMIENTO DE UNA OBJETO</font>
- <font color ="magenta">El orden de los metodos en el archivo del programa es irrelevante</font>
- **La primera letra del nombre de una clase esta en mayusculas**. Si hay mas de una palabra, <mark style="background: #D2B3FFA6;">se debe usar mayuscula para la primera letra de cada palabra</mark> . ("*MyFirstJavaClass*")
- los nombres de todos los métodos en la sintaxis de Java comienzan con una letra minúscula. Cuando se usan varias palabras, las letras subsiguientes se escriben en mayúsculas ("*public static void myFirstMethodName*")
- los archivos se guardan con el nombre de la clase y la extensión .java ("*MyFirstJavaClass.java*")
- En la sintaxis de Java, existen delimitadores "{...}", los cuales <mark style="background: #D2B3FFA6;">denotan un bloque de codigo</mark> y una <mark style="background: #D2B3FFA6;">nueva area de codigo</mark>
- Cada declaración de código debe terminar con un punto y coma (";")