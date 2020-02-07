# 1 Introducción

### 1.1 Procesadores de lenguaje

#### Compilador

programa que puede leer un programa en un lenguaje (el lenguaje fuente) y traducirlo en un programa equivalente en otro lenguaje (el lenguaje destino).

Reporta errores en el programa fuente durante la traducción.

El programa debe ser ejecutado por el usuario para procesar entradas y con ellas salidas.

***Por lo general el lenguaje producido por un compilador es mas rápido que un interprete.***



#### Intérprete

el intérprete nos da la apariencia de ejecutar directamente operaciones especificadas en el programa de origen (fuente) con las entradas proporcionadas el usuario.

***Por lo regular el interprete puede ofrecer mejores diagnósticos de error, ejecuta programa fuente instrucción a instrucción.***



### 1.2 Estructura de un compilador

**[Análisis](./analisis.md)** (front-end): divide el programa fuente en componentes, genera una representación intermedia y durante dicho análisis puede detectar si el programa fuente esta mal formado sistemáticamente, si es así entonces deberá informar al usuario para que los pueda corregir. Esta información la almacena en una estructura llamada tabla de símbolos (que pasara a la parte de síntesis).

**[Síntesis](./sintesis.md)** (back-end): Construye  programa destino a partir de la representación intermedia y la tabla de símbolos.



**La tabla de símbolos es utilizada durante todas las fases del compilador.**

En ocasiones puede integrar una fase de optimización, la cual esta entre el front-end y el back-end.

