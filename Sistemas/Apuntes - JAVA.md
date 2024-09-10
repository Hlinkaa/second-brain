---
tags:
  - Java
Lenguaje: Java
---
## Palabras Clave
---
- Clases
- Objetos
- Estado
- Comportamiento
- Método%%/procedimiento/función%%
- Matrices
- Variables

![[public-static-void-main|10000]]

# Clases
---
#Clases-Java
Lorem Ipsum

# Objetos
---
#Objetos-Java

Lorem Ipsum
# Estado
---
#Estado-Java

Lorem Ipsum
# Comportamiento
---
#Comportamiento-Java

Lorem Ipsum
# Métodos
---
#Metodos-Java

Lorem Ipsum
# Matrices
---
#Matrcies-Java

Lorem Ipsum
# Sintaxis
---
#SIntaxis-Java 

- el **<font color ="magenta">NOMBRE DEL ARCHIVO</font>** debe ser **<font color ="magenta">IDENTICO</font>** al **<font color = "magenta">NOMBRE DE LA CLASE</font>**
- la mayoría de las veces, cada clase esta en un archivo separado con una extensión <font color = "magenta">.JAVA</font>. Los archivos de clase generalmente se agrupan en carpetas denominadas <font color ="magenta">PAQUETES</font>
- Java es <font color ="magenta">CASE SENSITIVE</font>, esto quiere decir que <font color ="magenta">distingue de mayusculas y minusculas</font>. *String != string*.
- El comienzo del procesamiento del programa Java **SIEMPRE** empieza en el método principal : %% Apple Case = primera letra en mayusc %%
 
```java
public static void main (String[] args)
```


> [!NOTE] Importante
> El método *main()* es una parte requerida de **cualquier programa de Java**

- Metodo es una secuencia de comandos. Los metodos definen el <font color ="magenta">COMPORTAMIENTO DE UNA OBJETO</font>
- <font color ="magenta">El orden de los metodos en el archivo del programa es irrelevante</font>
- **La primera letra del nombre de una clase esta en mayusculas**. Si hay mas de una palabra, <mark style="background: #D2B3FFA6;">se debe usar mayuscula para la primera letra de cada palabra</mark> . ("*MyFirstJavaClass*")
- los nombres de todos los metodos en la sintaxiss de Java comienzan con una letra minuscula. Cuando se usan varias palabras, las letras subsiguientes se escriben en mayusculas ("*public static void myFirstMethodName*")
- los archivos se guardan con el nombre de la clase y la extension .java ("*MyFirstJavaClass.java*")
- En la sintaxis de Java, existen delimitadores "{...}", los cuales <mark style="background: #D2B3FFA6;">denotan un bloque de codigo</mark> y una <mark style="background: #D2B3FFA6;">nueva area de codigo</mark>
- Cada declaracion de codigo debe terminar con un punto y coma (";")

# Tipos de Datos
---
#TiposDeDatos-Java

Existen **8 tipos de datos** los cuales tambien se conocen como **datos primitivos** y son :

- byte
- short
- int
- long
- char
- float
- double
- boolean

#### Enteros
Este grupo incluye **byte, short, int y long**. Estos tipos de datos nos permiten trabajar con numeros enteros ya sean positivos o negativos.

| NOMBRE | BYTES | RANGO                                                      |
| ------ | ----- | ---------------------------------------------------------- |
| long   | 8     | $$–9,223,372,036,854,775,808 a 9,223,372,036,854,775,807$$ |
| int    | 4     | $$–2,147,483,648 a 2,147,483,647$$                         |
| short  | 2     | $$–32,768 to 32,767$$                                      |
| byte   | 1     | $$-128 a 127$$                                             |
%% En la mayoria de los casos usaremos el tipo de dato INT para numeros positivos %%

>[!NOTE] Ejemplo
```java
byte diasMes = 31; //Aproximadamente
short diasLustro = (12 * 31) * 5;
int velocidadLuz = 299792458;
long añoLuz = velocidadLuz * 365;
```

#### Flotantes/Decimales
Este grupo incluye **float** y **double**. Estos tipos de datos nos permiten trabajar con numeors los cuales posean punto decimal ya sean positivos o negativos.

| NOMBRE | BYTES | RANGO APROXIMADO         |
| ------ | ----- | ------------------------ |
| double | 8     | $$4.9e–324 to 1.8e+308$$ |
| float  | 4     | $$1.4e–045 to 3.4e+038$$ |

>[!NOTE] Ejemplo
```java
float pi = 3.1415926535f;
double e = 2.718281828459045235360;
```

#### Caracteres
En el grupo de caracteres unicamente encotraremos el tipo de dato **char**. Este tipo de datos nos permitira trabajar con caracteres.

>[!NOTE] Ejemplo
```java
char letraA = 'a';
char letraANumerico = 61;
```

#### Booleanos
Al igual que el [grupo de caracteres](#Caracteres), en el el grupo de booleanos unicamente encontraremos un tipo de dato, el **boolean**. **Este tipo de datos nos permitira trabajar con valores logicos, verdaderos o falso.**

>[!NOTE] Ejemplo
```java
boolean verdadero = true;
boolean falso = false;
```

