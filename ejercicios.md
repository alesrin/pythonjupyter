```python
# EJERCICIO 1 NUMPY

import numpy as np

# 1. Array unidimensional con el nombre de los productos
productos = np.array(["Smartphone", "Tablet", "Laptop", "Auriculares", "Teclado"])
print("Nombres de los productos:", productos)

# 2. Array bidimensional con la cantidad en stock de cada producto
stock = np.array([[50, 30, 15, 40, 60]])  # Stock por cada producto en diferentes almacenes (únicamente un almacén en este caso)
print("Cantidad en stock de cada producto:\n", stock)

# 3. Array tridimensional para registrar las ventas de cada producto durante una semana (3 días)
ventas = np.array([[[5, 3, 2, 6, 4], [7, 4, 1, 8, 5], [6, 2, 3, 5, 4]]])
print("Ventas durante 3 días:\n", ventas)

# 4. Array de ceros para los productos no vendidos hoy
no_vendidos_hoy = np.zeros(5)
print("Productos no vendidos hoy:\n", no_vendidos_hoy)

# 5. Array de unos para los productos que están en promoción
promocion = np.array([1, 0, 0, 0, 1])  # Smartphone y Teclado están en promoción
print("Productos en promoción:\n", promocion)

# 6. Array con un rango de precios de productos entre 50 y 1000 con paso de 50
precios_rango = np.arange(50, 1000, 50)
print("Precios de productos con un rango de 50 a 1000:\n", precios_rango)

# 7. Array de precios aleatorios entre 100 y 500 unidades monetarias para 5 productos
precios_aleatorios = np.random.randint(100, 500, size=5)
print("Precios aleatorios de productos entre 100 y 500 unidades monetarias:\n", precios_aleatorios)

# 8. Array de números enteros aleatorios para la cantidad vendida de cada producto hoy
cantidad_vendida = np.random.randint(1, 10, size=5)
print("Unidades vendidas hoy de cada producto:\n", cantidad_vendida)

# 9. Array vacío para almacenar los valores de descuento
descuentos = np.empty((5, 1))
print("Array vacío para los descuentos:\n", descuentos)

# 10. Array con valores espaciados para analizar el cambio en las ventas (de 0 a 1000 con 5 puntos)
ventas_espaciadas = np.linspace(0, 1000, 5)
print("Ventas totales distribuidas en 5 puntos entre 0 y 1000:\n", ventas_espaciadas)

```

    Nombres de los productos: ['Smartphone' 'Tablet' 'Laptop' 'Auriculares' 'Teclado']
    Cantidad en stock de cada producto:
     [[50 30 15 40 60]]
    Ventas durante 3 días:
     [[[5 3 2 6 4]
      [7 4 1 8 5]
      [6 2 3 5 4]]]
    Productos no vendidos hoy:
     [0. 0. 0. 0. 0.]
    Productos en promoción:
     [1 0 0 0 1]
    Precios de productos con un rango de 50 a 1000:
     [ 50 100 150 200 250 300 350 400 450 500 550 600 650 700 750 800 850 900
     950]
    Precios aleatorios de productos entre 100 y 500 unidades monetarias:
     [209 279 190 280 216]
    Unidades vendidas hoy de cada producto:
     [2 1 4 4 1]
    Array vacío para los descuentos:
     [[1.e-323]
     [3.e-323]
     [3.e-323]
     [4.e-323]
     [5.e-324]]
    Ventas totales distribuidas en 5 puntos entre 0 y 1000:
     [   0.  250.  500.  750. 1000.]

