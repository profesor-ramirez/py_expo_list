# Exposición sobre Clases, Métodos, Funciones, Acceso y Gestión de Ficheros, Manejo de Excepciones y Errores en Python

## 1. Métodos en Python
- **Definición**: Qué es un método y su diferencia con una función.
- **Métodos de instancias y de clase**:
  - Métodos de instancia: Definición y uso del primer argumento `self`.
  - Métodos de clase: Uso del decorador `@classmethod` y el argumento `cls`.
  - Métodos estáticos: Uso del decorador `@staticmethod`, sin necesidad de `self` o `cls`.
- **Métodos incorporados**:
  - Métodos comunes para tipos básicos (listas, cadenas, diccionarios, etc.), como `list.append()`, `str.lower()`, `dict.get()`.
  - Buenas prácticas para crear métodos dentro de clases.

## 2. Funciones en Python
- **Definición**: Qué es una función y su estructura básica.
- **Sintaxis básica**: Declaración con `def`, nombre, parámetros y retorno.
- **Parámetros**:
  - Parámetros obligatorios.
  - Parámetros opcionales con valores por defecto.
  - Argumentos posicionales (`*args`) y argumentos con nombre (`**kwargs`).
- **Funciones lambda**:
  - Sintaxis de funciones lambda para operaciones simples.
- **Funciones de orden superior**:
  - Funciones como `map()`, `filter()`, `reduce()`, y cómo toman otras funciones como parámetros.
- **Retorno múltiple**: Devolver múltiples valores en una función usando tuplas.

## 3. Acceso y Gestión de Ficheros en Python
- **Apertura de archivos**:
  - Uso de `open()` para leer (`'r'`), escribir (`'w'`), y agregar (`'a'`) en archivos.
- **Lectura de archivos**:
  - Métodos para leer archivos: `read()`, `readline()`, `readlines()`.
- **Escritura en archivos**:
  - Escribir datos con `write()` y `writelines()`.
  - Creación de nuevos archivos.
- **Cierre de archivos**:
  - Importancia de cerrar los archivos con `close()`.
  - Uso del gestor de contexto `with` para manejo seguro de archivos.
- **Modos adicionales**: Modos binarios (`'rb'`, `'wb'`) y cómo trabajar con ellos.
- **Gestión de rutas de archivo**:
  - Uso de módulos como `os` y `pathlib` para manejar rutas de manera eficiente.
  
## 4. Manejo de Excepciones y Errores en Python
- **Definición de excepciones**: Qué es una excepción y diferencia entre error y excepción.
- **Bloque `try-except`**:
  - Uso básico de `try` y `except` para capturar errores.
  - Manejo de excepciones específicas (`FileNotFoundError`, `ValueError`, etc.).
  - Uso de `else` para código que debe ejecutarse si no hay excepciones.
  - Uso de `finally` para ejecutar código sin importar si ocurre una excepción o no.
- **Levantar excepciones**:
  - Uso de `raise` para lanzar excepciones personalizadas.
- **Crear excepciones personalizadas**:
  - Cómo definir una excepción personalizada mediante clases.

## 5. Asignación práctica
1. Escribe un programa que lea un archivo CSV llamado clientes.csv que contiene una lista de clientes. El archivo tiene columnas separadas por comas (nombre, edad, email). El programa debe:
    - Leer el archivo línea por línea.
    - Capturar excepciones si una línea tiene un formato incorrecto (por ejemplo, falta un campo o hay demasiados).
    - Contenido del fichero clientes.csv:
``` 
Nombre,Edad,Email
Juan Pérez,30,juan.perez@email.com
Ana Gómez,25,ana.gomez@email.com
Carlos Ruiz,28
María Fernández,35,maria.fernandez@email.com
```

2. De acuerdo a las siguientes funciones, se necesita convertirlas en una expresión lambda y aplicarlas al arreglo:

``` 
numeros = [1, 2, 3, 4, 5, 6]

# Usa la función filter para filtrar los números pares de una lista con la función lambda para filtrar los números pares de la lista llamada numeros.

def es_par(n):
    return n % 2 == 0

# Aplica la función lambda en cada uno de los números de la lista llamada numeros.
def al_cuadrado(n):
    return n ** 2

# Aplica la función lambda en cada uno de los números de la lista llamada numeros.
def suma(a, b):
    return a + b
``` 