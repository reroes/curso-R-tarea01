# Curso - R
## Tarea 01
### Descripción de la tarea

1. Una vez haya leido este archivo lo puede grabar en su disco duro use la funcion sink
2. Lea el archivo de datos de aves en el siguiente enlace: https://raw.githubusercontent.com/Ciespinosa/datos_practicas/master/Aves_temporal2.csv, usando la función read.csv
3. Guarde los datos en su disco duro, use la función write.csv
4. Queremos saber cuales son las 5 especies de aves que tiene mas individuos. 

a. Use la funcion colSums, para sumar los individuos de cada especie.  Puesto que la matriz de aves tiene dos columnas que son fecha y estacion, omitiremos esas dos primeras columnas.  Si usted le puso como nombre al objeto de los datos de aves: dAves (usted puede poner cualquier nombre), para omitir las dos primeras columnas seria dAves[,-(1:2)].

b. Para ordenar el vector resultante use la función sort y en argumentos incluya, decreasing = TRUE.

c. Par obtener las 5 especies mas abundantes, con el vector creado en b, defina cuantas especies quiere ver. Si le puso de nombre al vector nomA, use nomA[1:5], esto nos permitira obtener los elementos del 1 al 5.

5. Genere un reporte en el cual se diga cuales son las 5 especies con mayor abundancia. Use la funcion names, para obtener los nombres de las especies dominantes.

6. Agregue en el reporte el summary del objeto de aves.

7. Incluya en el informa una frase que diga: Luego del analisis desarrollado la especie mas dominante es xx(incluir con codigo la especie mas dominante), con un total de xx (incluir con codigo el numero de individuos de esa especie).
