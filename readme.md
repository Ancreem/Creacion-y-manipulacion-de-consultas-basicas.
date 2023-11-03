### Consultas sobre una tabla

1. Lista el nombre de todos los productos que hay en la tabla `producto`.

   ```sql
    select nombre as producto_nombre from producto;
   ```
2. Lista los nombres y los precios de todos los productos de la tabla `producto`.

   ```sql
    select nombre, precio as producto_nombrePrecio from producto;
   ```
3. Lista todas las columnas de la tabla `producto`.

   ```sql
    select id as id_pedido, nombre as nombre_pedido, precio as precio_pedido, id_fabricante as id_producto from producto;
   ```
4. Lista el nombre de los productos, el `precio` en euros y el `precio` en dólares estadounidenses (USD).

   ```sql
    select id as id_producto, precio * 1.07 as precio_dolar, precio * 1.09 as precio_euro from producto;
   ```
5. Lista el nombre de los productos, el `precio` en euros y el `precio` en dólares estadounidenses (USD). Utiliza los siguientes alias para las columnas: `nombre de producto`, `euros`, `dólares`.

   ```sql
    select nombre as nombre_de_producto, precio * 1.09 as euros, precio * 1.07 dolares from producto;
   ```
6. Lista los nombres y los precios de todos los productos de la tabla `producto`, convirtiendo los nombres a mayúscula.

   ```sql
    select upper(nombre) as nombre_en_mayusculas, precio as precio_producto from producto;
   ```
7. Lista los nombres y los precios de todos los productos de la tabla `producto`, convirtiendo los nombres a minúscula.

   ```sql
    select lower(nombre) as nombre_en_minuscula, precio as precio_producto from prod
ucto;
   ```
8. Lista el nombre de todos los fabricantes en una columna, y en otra columna obtenga en mayúsculas los dos primeros caracteres del nombre del fabricante.

   ```sql
   # Consulta Aqui
   ```
9. Lista los nombres y los precios de todos los `productos` de la tabla producto, redondeando el valor del precio.

   ```sql
    select nombre as nombre_producto, round(precio) as precio_producto_redondeado from producto;
   ```
10. Lista los nombres y los precios de todos los `productos` de la tabla producto, truncando el valor del precio para mostrarlo sin ninguna cifra decimal.

   ```sql
   # Consulta Aqui
   ```
11. Lista el identificador de los fabricantes que tienen productos en la tabla `producto`.

   ```sql
   # Consulta Aqui
   ```
12. Lista el identificador de los fabricantes que tienen `productos` en la tabla producto, eliminando los identificadores que aparecen repetidos.

   ```sql
   # Consulta Aqui
   ```
13. Lista los nombres de los fabricantes ordenados de forma ascendente.

   ```sql
   # Consulta Aqui
   ```
14. Lista los nombres de los fabricantes ordenados de forma descendente.

   ```sql
   # Consulta Aqui
   ```
15. Lista los nombres de los productos ordenados en primer lugar por el nombre de forma ascendente y en segundo lugar por el precio de forma descendente.

   ```sql
   # Consulta Aqui
   ```
16. Devuelve una lista con las 5 primeras filas de la tabla `fabricante`.

   ```sql
   # Consulta Aqui
   ```
17. Devuelve una lista con 2 filas a partir de la cuarta fila de la tabla `fabricante`. La cuarta fila también se debe incluir en la respuesta.

   ```sql
   # Consulta Aqui
   ```
18. Lista el nombre y el precio del producto más barato. (Utilice solamente las cláusulas `ORDER BY` y `LIMIT`)

   ```sql
   # Consulta Aqui
   ```
19. Lista el nombre y el precio del producto más caro. (Utilice solamente las cláusulas `ORDER BY` y `LIMIT`)

   ```sql
   # Consulta Aqui
   ```
20. Lista el nombre de todos los productos del fabricante cuyo identificador de fabricante es igual a 2.

   ```sql
   # Consulta Aqui
   ```
   
