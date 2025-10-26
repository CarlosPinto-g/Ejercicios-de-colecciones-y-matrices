# Ejercicios de colecciones y matrices
##  N°1 Arreglo de reales 
```python
# Algoritmo para calcular el promedio de un arreglo de números reales

# Pedir la cantidad de elementos
n = int(input("¿Cuántos números vas a ingresar? "))

# Crear una lista vacía
numeros = []

# Ingresar los números
for i in range(n):
    num = float(input(f"Ingrese el número {i + 1}: "))
    numeros.append(num)

# Calcular el promedio
promedio = sum(numeros) / len(numeros)

# Mostrar el resultado
print(f"El promedio de los números ingresados es: {promedio}")
```
Foto de la consola 1
[![Captura-de-pantalla-56.png](https://i.postimg.cc/kgGRkqjM/Captura-de-pantalla-56.png)](https://postimg.cc/pmNdjbb3)

## N°2 Producto punto de dos arreglos
```python
# Producto punto de dos arreglos de números reales

# Ingresar los arreglos
v = [float(x) for x in input("Ingresa los valores de v separados por espacio: ").split()]
w = [float(x) for x in input("Ingresa los valores de w separados por espacio: ").split()]

# Verificar que tengan el mismo tamaño
if len(v) != len(w):
    print("Los arreglos deben tener el mismo tamaño.")
else:
    producto_punto = 0
    for i in range(len(v)):
        producto_punto += v[i] * w[i]

    print("El producto punto de v y w es:", producto_punto)
```
Foto de la consola 2
[![Captura-de-pantalla-57.png](https://i.postimg.cc/SKqFnNwY/Captura-de-pantalla-57.png)](https://postimg.cc/VJ7HT1sz)

## N°3 Producto directo de dos arreglos
```python
# Producto directo de dos arreglos de números reales

# Ingresar los arreglos
v = [float(x) for x in input("Ingresa los valores de v separados por espacio: ").split()]
w = [float(x) for x in input("Ingresa los valores de w separados por espacio: ").split()]

# Verificar que tengan el mismo tamaño
if len(v) != len(w):
    print("Los arreglos deben tener el mismo tamaño.")
else:
    producto_directo = []
    for i in range(len(v)):
        producto_directo.append(v[i] * w[i])

    print("El producto directo de v y w es:", producto_directo)
```
Foto de la cansola 3
[![Captura-de-pantalla-58.png](https://i.postimg.cc/BnzpzhC8/Captura-de-pantalla-58.png)](https://postimg.cc/dh8Gkjpv)

