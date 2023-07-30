<font style="vertical-align: inherit;"><font style="vertical-align: inherit;">phyton basico</font></font>

* * *



Python es un lenguaje de programación de alto nivel, interpretado y versátil, que se ha vuelto muy popular debido a su facilidad de lectura y escritura de código. Es utilizado en diversos campos, como desarrollo web, análisis de datos, inteligencia artificial, automatización y mucho más.

A continuación, te mostraré algunos conceptos básicos y ejemplos para empezar a familiarizarte con Python:

1. **Instalación y configuración:** Para empezar, debes instalar Python en tu computadora si aún no lo has hecho. Puedes descargar la última versión estable de Python desde el sitio oficial ( [https://www.python.org/downloads/](https://www.python.org/downloads/) ) y seguir las instrucciones para la instalación.
    
2. **Ejecución de Python:** Una vez instalado, abre la terminal o el intérprete de comandos de su sistema operativo y escribe `python`. Esto iniciará el intérprete de Python, donde podrá ingresar y ejecutar comandos o programas de Python.
    
3. **Imprimir en pantalla:** El comando `print()`se utiliza para mostrar mensajes o resultados en la pantalla. Aquí tienes un ejemplo sencillo:
    

```python
print("¡Hola, mundo!")
```

4. **Variables:** Las variables se utilizan para almacenar valores en la memoria. En Python, no es necesario declarar el tipo de variable, ya que se infiere automáticamente. Puedes asignar valores a variables de la siguiente manera:

```python
nombre = "Juan"
edad = 30
altura = 1.75
```

5. **Operaciones matemáticas básicas:** Python permite realizar operaciones matemáticas básicas, como suma, resta, multiplicación y división. Aquí tienes un ejemplo:

```python
a = 10
b = 5

suma = a + b
resta = a - b
multiplicacion = a * b
division = a / b

print("Suma:", suma)
print("Resta:", resta)
print("Multiplicación:", multiplicacion)
print("División:", division)
```

6. **Condicionales:** Los condicionales permiten tomar decisiones basadas en ciertas condiciones. En Python, se utilizan las palabras clave `if`, `elif`(opcional) y `else`. Aquí tienes un ejemplo:

```python
edad = 18

if edad >= 18:
    print("Eres mayor de edad.")
else:
    print("Eres menor de edad.")
```

7. **Bucles:** Los bucles te permiten repetir un bloque de código varias veces. Python tiene dos tipos principales de bucles: `for`y `while`. Aquí tienes un ejemplo con un bucle `for`:

```python
for i in range(5):
    print("Número:", i)
```

Estos son solo algunos de los conceptos básicos de Python. A medida que avanza, podrá más explorar sobre funciones, listas, diccionarios, clases, entre otros. Python cuenta con una amplia biblioteca estándar que proporciona una gran cantidad de funcionalidades útiles para diversas tareas.

Ejercicios hechos en google colab:

![[1-.png]]


![[2-.png]]


![[3-.png]]

EJERCIO FINAL DIA 2!!!!

SORTEO!!!!!

Ejercicio en parejas

```Python
import random

animals  = ['Perro', 'Gato', 'Delfin', 'Tiburon', 'Jirafa']

numbers = [1, 2, 3, 4]

  
def lottery():

    lottery = input("Ingresar su numero de loteria: ")

lottery()

tamano_lista = 4

rango_minimo = 1

rango_maximo = 4

  
lista_aleatoria = [random.randint(rango_minimo, rango_maximo) for _ in range(tamano_lista)]

  
if lottery == lista_aleatoria:

    print("Ganaste la loteria")

else:

  print("Lo sentimos esta es la lista de numeros de loteria que ganaron: ", lista_aleatoria)

  
def animal():

    animal = input("Ingrese su Animal: ")

animal()

  
lista_animal =

  
if animal == lista_animal:

     print("Ganaste otro boleto")

else:

     print("Lo sentimos el animal ganador es: ", random.choice(animals))







