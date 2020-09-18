# INTRODUCCION
**Programacion**: Es el proceso de tomar un algoritmo y codificarlo en una notación, un lenguaje de programación, 
              de modo que pueda ser ejecutado por una computadora. 
              
**Codigo**: escribir instrucciones para la computadora.

**Ejemplo de un problema**: Registrar a todos los asistentes de un curso. Para esto se crearia un programa donde 
                        el asistente ingresa los datos y el sistema los va acomodando en una tabla automaticamente 
                        en vez de hacerlo a mano.
### RAMAS DE LA PROGRAMACION

**WEB**: Wordpress (cms) paginas web; aplicacion web.
     Es una interfaz universal y no depende de un sistema operativo.

**MOVIL**: Aplicaciones para celulares. Se puede utilizar los lenguajes Java, JavaScript, C#, entre otros.

**ESCRITORIO**: Aplicaciones nativas para el sistema operativo Windows, MACOS, LINUX.

**VIDEOJUEGOS**: Programacion en videjuegos.

**REALIDAD VIRTUAL**: Programacion enfocada a los sistemas de VR o realidad virtual.

**REALIDAD AUMENTADA**: Programacion enfocada a los sistemas que combinan el entorno real con el entorno virtual.
                    Ejemplo: Pokemon GO

**INTELIGENCIA ARTIFICIAL**: Donde las computadoras pueden tomar decisiones por si mismsas

**SEGURIDAD INFORMATICA**: Proteger los sistemas informaticos aplicando distintas tecnicas de seguridad

### LENGUAJES DE PROGRAMACION

**LENGUAJE INFORMATICO**: Es cualquier lenguaje que la computadora pueda entender y tambien le de instrucciones.

**LENGUAJE DE PROGRAMACION**: Es capaz de ejecutar un algoritmo.

**COMPILADO**: Convierte el codigo a binarios que lee el sistema operativo.

**INTERPRETE**: Requiere de un programa que lea la instruccion del codigo en tiempo real y la ejecuta.

**ALTO NIVEL**: Abstraccion del lenguaje de maquina para ser comprendidos por humanos.

**BAJO NIVEL**: Interactuan directamente sobre el hardware (lenguaje maquina, ensamblador).

**PARADIGMAS DE PROGRAMACION**: son diferentes estilos de usar la programacion para resolver un problema
  -Estructurada: Secuencial, usa ciclos y condicionales
  -Recreativa: Observa flujo de datos asincronicos y reacciona frente a sus cambios.
  -Programacion Orientada a Objetos (POO): Divide los componentes del programa en objetos que tienen datos
      y comportamiento que se comunican entre si.
  -Funcional: Divide el programa en tareas pequeñas que son ejecutados por funciones.

### HERRAMIENTAS

**EDITOR**: Es un programa sencillo para editar codigo.

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
```SH

```
### CARACTERISTICAS DE ALGORITMO
```SH

```
### DESARROLLO DE ALGORITMO CON PSEUDOCODIGO
**PSEUDOCÓDIGO**: Es decir en palabras que entendemos nosotros los humanos de como podemos resolver un problema o necesidad.

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
