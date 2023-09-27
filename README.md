#   Tienda Online de varias categorías

El conjunto de datos es obtenido por medio de la plataforma Kaggle, la cual, durante un período de 7 meses, desde octubre de 2019 hasta abril de 2020, sin embargo, solo se utilizó el mes de octubre, se recopilaron datos sobre el comportamiento de compras en línea en una tienda de comercio electrónico de amplias categorías. Estos datos abarcan una variedad de actividades realizadas por los usuarios en la plataforma durante ese período.
Las variables clave en la base de datos incluyen:
•	Fecha: Indica la fecha y la hora en la que el dato fue recolectado
•	Categoría: Indica la clasificación o tipo de productos disponibles en la tienda en línea. Por ejemplo, electrónica, ropa, hogar, etc.
•	Marca: Representa las marcas específicas de los productos que se ofrecen en la tienda en línea. Esto puede ayudar a identificar las preferencias de los usuarios por marcas particulares.
•	Precio: Indica el precio de los productos en la tienda. Esta información es crucial para analizar los patrones de gasto de los usuarios y sus preferencias de compra.
•	Tipo de acción: Muestra si el usuario vio, agregó al carro, elimino del carro o completo la compra de los diferentes productos


# Cuál es su problemática:
El problema principal al que se puede dar solución a la tienda en línea, es a los problemas de inventario que pueda tener la tienda, observando los patrones de navegación y las acciones que realizan los usuarios.   


# Que se encuentra en su repositorio
En este repositorio se puede encontrar el proceso de cargue y lectura de la base de datos en Python por medio de GoogleColab, donde tambien se realizó el proceso de limpieza y visualziación de los datos, como tambien el proceso de transformarlo a SQL para poder realizar el proceso del CRUD

# Cuantos datos tomó, de que son y cuantas características tienen
La base de datos que se utilizó cuenta con 42.448.763, sin embargo se trabajo con una porcion de los datos, creando una copia de 600.000 datos

# Que encontró en los datos

Despues de realizar la limpieza de los datos nulos se pudo encontrar que, el 95.3% de las usuarios que ingresan a la página web solo observan los porductos disponibles pero no realizan ninguna compra.

Se encontró que las marcas que generan mas acción dentro de la página son Apple con un 28.9%, Samsung con un 32.7% y Xiaomi con un 16.3%

# Cómo su descubrimiento podría dar valor a una empresa:
El valor que se generaría a través de los datos es la optimización de la experiencia de usuarios, obtener información certera para la toma de decisiones enfocada en el inventario y así poder generar estrategias de marketing personalizadas.