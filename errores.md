# Errores en la practica

1- SELECT * trae todas las columnas, no todas las filas.

2- COUNT(columna) cuenta filas donde esa columna no es NULL, no columnas.

3- Si el SELECT tiene una agregación, todo lo demás tiene que ser otra agregación o ir en un GROUP BY.

4- MIN y MAX devuelven un valor, no filas ni productos.

5- Con enteros, AVG trunca los decimales; no los redondea.
