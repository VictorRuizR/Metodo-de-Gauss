\# Método de Gauss (Eliminación Gaussiana)

Programa que resuelve sistemas de ecuaciones lineales mediante el \*\*Método de Gauss\*\*: triangulación de la matriz aumentada y sustitución regresiva.



\*\*Autor:\*\* Víctor Ruiz R. — \[Métodos Numéricos / 03BS]



\## Lenguaje de programación ##



\*\*Java\*\* (JDK 17 o superior recomendado).



\## Estructura del proyecto (diseño modular) ##



|        Archivo       |                                  Descripción                                      |

|----------------------|-----------------------------------------------------------------------------------|

| "DatosMatriz.java"   | Define los datos: la matriz aumentada \[A \\| b] del sistema.                     |

| "Gauss.java"         | Contiene la lógica: "eliminacionGaussiana()" y "sustitucionRegresiva()]".         |

| "LanzadorGauss.java" | Clase principal con el método "main"; coordina la ejecución e imprime resultados. |



\## Cómo compilar y ejecutar ##



\### Desde la terminal ##

1\. Clona el repositorio o descarga los archivos en una misma carpeta.

2\. Abre una terminal en esa carpeta.

3\. Compila:

```bash

&#x20;  javac \*.java

```

4\. Ejecuta:

```bash

&#x20;  java LanzadorGauss

```



\### Desde IntelliJ IDEA ###

1\. Abre la carpeta del proyecto (\*File → Open\*).

2\. Abre "LanzadorGauss.java".

3\. Presiona el botón verde ▶ junto al método "main".



\## Ejemplo de prueba ##



Sistema de ecuaciones:



\------------------------------

(3x1 - 0.1x2 - 0.2x3 =  7.85 )

(0.1x1 + 7x2 - 0.3x3 = -19.3 )

(0.3x1 - 0.2x2 + 10x3 =  71.4)

\------------------------------



Salida por consola:



\------------------------

Soluciones del sistema:

x1 = 3.0

x2 = -2.5

x3 = 7.000000000000001

\-----------------------



\## Funcionamiento ##



1\. \*\*Eliminación gaussiana:\*\* convierte en ceros los elementos debajo de la diagonal principal (matriz triangular superior).

2\. \*\*Sustitución regresiva:\*\* despeja las incógnitas desde la última ecuación hacia la primera.

