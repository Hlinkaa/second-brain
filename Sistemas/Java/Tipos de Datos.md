---
Lenguaje: Java
Fecha: 10/09/2024
Fuente: Pensando la Computación como un Científico
tags:
  - Java
  - TiposDeDatos-Java
---
Existen **8 tipos de datos** los cuales también se conocen como **datos primitivos** y son :

- byte
- short
- int
- long
- char
- float
- double
- boolean

#### Enteros
Este grupo incluye **byte, short, int y long**. Estos tipos de datos nos permiten trabajar con números enteros ya sean positivos o negativos.

| NOMBRE | BYTES | RANGO                                                      |
| ------ | ----- | ---------------------------------------------------------- |
| long   | 8     | $$–9,223,372,036,854,775,808 a 9,223,372,036,854,775,807$$ |
| int    | 4     | $$–2,147,483,648 a 2,147,483,647$$                         |
| short  | 2     | $$–32,768 to 32,767$$                                      |
| byte   | 1     | $$-128 a 127$$                                             |
%% En la mayoría de los casos usaremos el tipo de dato INT para números positivos %%

>[!NOTE] Ejemplo
```java
byte diasMes = 31; //Aproximadamente
short diasLustro = (12 * 31) * 5;
int velocidadLuz = 299792458;
long añoLuz = velocidadLuz * 365;
```

#### Flotantes/Decimales
Este grupo incluye **float** y **double**. Estos tipos de datos nos permiten trabajar con números los cuales posean punto decimal ya sean positivos o negativos.

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
En el grupo de caracteres únicamente encontraremos el tipo de dato **char**. Este tipo de datos nos permitirá trabajar con caracteres.

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

# Referencias
- [[Pensando la Computación como un Científico (con Java)]]