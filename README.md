# INTRODUCCION
**Programacion**: Es el proceso de tomar un algoritmo y codificarlo en una notación, un lenguaje de programación, 
              de modo que pueda ser ejecutado por una computadora. 
              
**Codigo**: escribir instrucciones para la computadora.

**Ejemplo de un problema**: Registrar a todos los asistentes de un curso. Para esto se crearia un programa donde 
                        el asistente ingresa los datos y el sistema los va acomodando en una tabla automaticamente 
                        en vez de hacerlo a mano.
### RAMAS DE LA PROGRAMACION

**Web**: Wordpress (cms) paginas web; aplicacion web.
     Es una interfaz universal y no depende de un sistema operativo.

**Movil**: Aplicaciones para celulares. Se puede utilizar los lenguajes Java, JavaScript, C#, entre otros.

**Escritorio**: Aplicaciones nativas para el sistema operativo Windows, MACOS, LINUX.

**Videojuegos**: Programacion en videjuegos.

**Realidad Virtual**: Programacion enfocada a los sistemas de VR o realidad virtual.

**Realidad Aumentada**: Programacion enfocada a los sistemas que combinan el entorno real con el entorno virtual.
                    Ejemplo: Pokemon GO

**Inteligencia Artificial**: Donde las computadoras pueden tomar decisiones por si mismsas

**Seguridad Informatica**: Proteger los sistemas informaticos aplicando distintas tecnicas de seguridad

### LENGUAJES DE PROGRAMACION

**Lenguaje informatico**: Es cualquier lenguaje que la computadora pueda entender y tambien le de instrucciones.

**Lenguaje de programacion**: Es capaz de ejecutar un algoritmo.

**Compilado**: Convierte el codigo a binarios que lee el sistema operativo.

**Interprete**: Requiere de un programa que lea la instruccion del codigo en tiempo real y la ejecuta.

**Alto nivel**: Abstraccion del lenguaje de maquina para ser comprendidos por humanos.

**Bajo nivel**: Interactuan directamente sobre el hardware (lenguaje maquina, ensamblador).

**Paradigmas de programacion**: son diferentes estilos de usar la programacion para resolver un problema
  -Estructurada: Secuencial, usa ciclos y condicionales
  -Recreativa: Observa flujo de datos asincronicos y reacciona frente a sus cambios.
  -Programacion Orientada a Objetos (POO): Divide los componentes del programa en objetos que tienen datos
      y comportamiento que se comunican entre si.
  -Funcional: Divide el programa en tareas pequeñas que son ejecutados por funciones.

### HERRAMIENTAS

**Editor**: Es un programa sencillo para editar codigo.

**IDE (Integrated Development Enviroment)Entorno integrado de desarrollo**: es un editor que se utilzia al 
    crear un proyecto ademas compila, Arroja errores y tiene entornos para hacer pruebas.
- Visual Studio
- Android Studio
- IntelliJ Idea
- Codepen
- Stackblitz
- Cloud9
- Code everywhere
- [repl.it](https://repl.it/n)
# ALGORITMOS
### DEFINICION
**Programacion**: Conjunto de sieres de pasos para resolver un problema o una necesidad.
Algoritmo: programacion
### CARACTERISTICAS DE ALGORITMO
**Definido**: Su salida es unica, siempre y cuando los parametros sean los mismos.
* Preciso.
* Legible
* **Finito**: Debe tener un inicio y un final.

**PARTES DE UN ALGORITMO**
* Entrada.
* Proceso.
* Salida: resultados

### DESARROLLO DE ALGORITMO CON PSEUDOCODIGO
**Pseudocódigo**: Es decir en palabras que entendemos nosotros los humanos de como podemos resolver un problema o necesidad.

**Como resolver un problema o necesidad**

1. Tener un enunciado del problema o necesidad claro, conciso y completo.
2. Analizar los datos que se van a procesar
   - Datos de entrada.
   - Datos de salida.
   - Formulas que procesaran los datos.
   - Datos de prueba.
3. Identificar varias soluciones posibles.
```SH
//Modulo = Residuo
ALGORITMO AÑO BISIESTO
Escribir "Ingrese el año:";
Leer año;
Si ((año modulo 4=0) y (año modulo 100<>0))
  o año modulo 400=0 entonces
    Escribir "el año es bisiesto";
  Si No
    Escribir"el año no es bisiesto",
  Fin Si
Fin algoritmo
```
### DESARROLLO DE ALGORITMO CON DIAGRAMA DE FLUJO
![](/algoritmo.png)
### DESARROLLO DE ALGORIMO CON PYTHON
##### CODIGO
```Python
print ("Digite el año: ")
anio = int (input())
if (anio % 4==0 and anio % 100 !=0) or anio % 400==0:
    print ("Año bisiesto")
else:
    print ("Año no bisiesto")
```
##### RESULTADO
```SH
Digite el año: 
2019
Año no bisiesto
---------------
Digite el año: 
2020
Año bisiesto
```
# VARIABLES Y TIPOS DE DATOS
### FUNCION DE LA PERSISTENCIA DE LOS DATOS
* **Bytes**: Conjunto de 8 bits.

* **Bit**: Unidad basica de informacion en todo sistema.

* **Procesador**: Decide la informacion y realiza operaciones.

* **Memoria**:
    * Ram: acceso aleatorio 
    * Rom: solo lectura.
    
* **Persistencia de datos**: Poder almacenar la informacion de tal manera que no se pierda.

### TIPOS DE DATOS
##### PRIMITIVOS

**Entero**: Numeros positivos o negativos que no tengan decimales. Se utiliza como **int**.

**Decimal**: Numeros con puntos decimales puede ser negativo o positivo. Se utiliza como **float**.

**Caracter**: Puede ser letras, simbolos o numeros. Se utiliza como **character**.

**Cadena de caracteres**: Es un texto que se compone de una cadena de caractesres. Se utiliza como **string**.

##### LÓGICOS

**Booleano**: Se utilizan cuando solo hay 2 opciones de respuesta en una pregunta sean estos como verdadero o falso. Se utiliza como True o False. Su objetivo es pptimizar el uso de la memoria RAM.

##### TIPOS DE DATOS EN ALGUNOS LENGUAJES DE PROGRAMACION

**Numericos sin signo**: Utilizan (+) o (-) valor absoluto (unsigned).

**Largo / Corto**: Se utilzia para darle dimension a los valores. Se utiliza como **long / short**.

**Double**: Es similar a float, pero se utiliza cuando la precisión de una variable de coma flotante no es suficiente. Se utiliza como **double**.

### EJEMPLO 1
```Python
print(10)
```
```SH
10
```
### EJEMPLO 2
```Python
print("Hola mundo")
```
```SH
Hola mundo
```
### CLASE ENTERO
```Python
print(type(15))
```
```SH
<class 'int'>
```
### CLASE CADENA
```Python
Print(type("Edwin"))
```
```SH
<class 'str'>
```
### CLASE BOOLEANO
```Python
Print(type(False))
```
```SH
<class 'bool'>
```

**Variable**: Espacios de memoria reservados para lamacenar un dato.

```
Dia= "Viernes"
Current_month="October"
```
**Decaracion de una variable**: asignarle un nombre.

Ejemplo:
```
current_month = "October"; 
dia = "Viernes"
```
**Consejo**: Tomar un estandard para declarar variables preferentemente en ingles y que la variable sea intuitiva.

### TIPOS DE ESCRITURA PARA LAS VARIABLES (ESTANDARES)
* **Camel case**: dayOfTheMonth = 25

* **Pascal case**: DayOfTheMonth = 25

* **Snake case**: day_of_the_month = 25

* **Kebab case**: day-of-the-month = 25

### EJEMPLO DE DECLARACION DE VARIABLE
##### EJEMPLO 1
```Python
nombre = "Beto"
print(nombre)
```

```SH
Beto
```
##### EJEMPLO 2
```Python
nombre = "Beto"
edad = 29
print(edad)
```
```SH
29
```

# OPERADORES
### OPERADORES ARITMETICOS
* Suma
```Python
a = 10
b = 5
print (a+b)
```
```
15
```
* Suma de variables
```Python
a = 10
b = 5
c= a+b
print (c)
```
```
15
```

* Resta
```Python
a = 10
b = 5
print (a-b)
```
```
5
```

* Multiplicacion
```Python
a = 10
b = 5
print (a*b)
```
```
50
```
* Division
```Python
a = 10
b = 5
print (a/b)
```
```
2.0
```
* Módulo %: residuo
```Python
a = 10
b = 5
print (a%b)
```
```
0
```







# CICLOS
## CODIGO
```Python
numero=7
Usuario=0
while usiario != numero
  usuario= int(input("Cual es el numero?"))
  if usuario > numero:
    print("Digita un numero menor")
  elsif usuario < numero
    pint("Digita un numero mayor")
  else
    print("Correcto")
```
## VALOR
```SH
Texto
```
[GitHubDocs](https://docs.github.com/es/github/writing-on-github/basic-writing-and-formatting-syntax)
