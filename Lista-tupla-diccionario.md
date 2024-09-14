# Exposición sobre Listas, Tuplas, Diccionarios, Métodos de Colecciones y Entrada de Datos en Python

## 1. Listas en Python
- **Definición**: Qué es una lista, características (mutables, ordenadas, permiten duplicados).
- **Sintaxis**: Creación de listas con `[]`.
- **Operaciones comunes**: 
  - Acceso por índice.
  - Modificación de elementos.
  - Agregar elementos: `append()`, `extend()`, `insert()`.
  - Eliminar elementos: `remove()`, `pop()`, `clear()`.
  - Slicing y copiado de listas.
- **Iteración sobre listas**: Uso de loops `for` y comprensiones de listas.

## 2. Tuplas en Python
- **Definición**: Qué es una tupla, características (inmutables, ordenadas, permiten duplicados).
- **Sintaxis**: Creación de tuplas con `()`.
- **Operaciones comunes**:
  - Acceso por índice.
  - Métodos disponibles: `count()`, `index()`.
  - Conversión entre listas y tuplas.
- **Uso de tuplas**: Casos de uso donde la inmutabilidad es útil

## 3. Diccionarios en Python
- **Definición**: Qué es un diccionario, características (desordenados, mutables, no permiten claves duplicadas).
- **Sintaxis**: Creación de diccionarios con `{}` y pares `clave: valor`.
- **Operaciones comunes**:
  - Acceso y modificación de valores por clave.
  - Agregar y eliminar pares clave-valor: `pop()`, `del`, `clear()`.
  - Métodos útiles: `keys()`, `values()`, `items()`, `get()`, `update()`.
- **Iteración sobre diccionarios**: Recorrer claves, valores o ambos con loops.

## 4. Métodos de Colecciones
- **Listas**:
  - `sort()`, `reverse()`, `count()`, `index()`.
- **Tuplas**:
  - Métodos limitados a `count()` e `index()`.
- **Diccionarios**:
  - `pop()`, `popitem()`, `setdefault()`, `update()`.
- **Operaciones comunes entre colecciones**:
  - Uso de `len()`, `in`, `not in` en listas, tuplas y diccionarios.
  - Comprensiones de listas, diccionarios y conjuntos.

## 5. Entrada de Datos
- **Entrada básica**:
  - Lectura de datos desde el usuario.
  - Conversión de tipos de entrada .
- **Validación de datos de entrada**:
  - Verificar que el tipo y el rango de valores sean correctos.
- **Entrada en listas y diccionarios**:
  - Agregar datos introducidos por el usuario a colecciones.

## 6. Asignación práctica
1. Supón que tienes que almacenar información básica de un usuario, como su nombre, apellido y fecha de nacimiento. Estos datos no deberían cambiar una vez que el usuario se ha registrado:
    - ¿Qué estructura de datos utilizarías en este escenario? 
    - Debes realizar el ejemplo en codigo.
2. Estás construyendo una base de datos sencilla para almacenar información sobre vehículos en una concesionaria. Cada vehículo tiene una matrícula única, un modelo y un año de fabricación. Debes implementar una solución que permita almacenar estos datos y luego consultar la información completa de un vehículo a partir de su matrícula.: 
    - ¿Cómo almacenarías la información de los vehículos?
    - ¿Qué estructura de datos te permitiría buscar un vehículo por su matrícula de manera eficiente?
3. Supón que estás almacenando las calificaciones de un estudiante a lo largo de un semestre. Las calificaciones pueden cambiar (si se corrigen o actualizan), o bien se pueden agregar nuevas calificaciones conforme avanzan las clases:
    - ¿Qué estructura de datos utilizarías en este escenario?
    - Debes realizar el ejemplo en codigo.
    


