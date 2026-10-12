# Errores en la practica

1- SELECT * trae todas las columnas, no todas las filas.

2- COUNT(columna) cuenta filas donde esa columna no es NULL, no columnas.

3- Si el SELECT tiene una agregación, todo lo demás tiene que ser otra agregación o ir en un GROUP BY.

4- MIN y MAX devuelven un valor, no filas ni productos.

5- Con enteros, AVG trunca los decimales; no los redondea.

6- CASE sin ELSE devuelve NULL en silencio.

7- Para agrupar por un CASE, repetís la expresión completa en el GROUP BY.

8- Si una columna conserva sus valores en el ELSE, usá ELSE columna, no una etiqueta fija.
