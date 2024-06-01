José Reyes - 1116842

Link del video: https://youtu.be/MQuJGgUvCOc

Read me – Data munging

Requerimientos
1.	Se requiere que el código lea el documento, para poder identificar los datos de importancia, va a conseguir el nombre del objeto y la diferencia que se esta buscando para luego almacenar cada dato en un array distinto.
2.	Se requiere que el código pueda conseguir durante la lectura del documento, los dos valores que va a restar para agregarlos directamente al array correspondiente
3.	El código deberá identificar cual es el valor menor dentro del array de las diferencias.
4.	El código mostrara por pantalla el nombre del objeto al que corresponde la diferencia más pequeña, seguida de su diferencia.

Criterios de aceptación
1.
-	Se almacenará el nombre del objeto en un array para esto
-	Se almacenará la diferencia de los dos valores que nos interesan
2.
-	Durante la lectura del documento, se obtendrán los dos valores de interés para restar
-	Cuando se vaya a introducir el dato dentro del array de las diferencias, se usa que el dato A – dato B es lo que se va a agregar al array.
3.
-	Una vez el array de las diferencias tenga todos los valores se usará una función que determina cual es este 
-	Obtiene su posición dentro del array.
4.
-	Se pasará por pantalla el nombre del objeto con el índice encontrado, al igual que su diferencia correspondiente.

Casos de prueba
1.	Si el documento pone la siguiente información [“objeto1   10   5\nobjeto2   50   10\nobjeto3   100   5”], entonces en el array de nombres del objeto se almacenará [“objeto1”, “objeto2”, “objeto3”] y en el de las diferencias [5, 40, 95].
2.	Si el documento pone la siguiente información [“objeto1   40   35\nobjeto2   50   39\nobjeto3   100   90”], entonces el código deberá tomar esos dos valores y le asignara al array de diferencias los valores 40 - 35, 50 – 39 y 100 – 90, es decir que en el array de diferencias [5, 11, 10].
3.	Si en el array de diferencias están los valores [9, 10, 100, 4, 6], entonces identificará como valor mínimo el 4 y el índice de la posición será igual a 3.
4.	Si en el array de nombres del objeto están estos valores [“objeto1”, “objeto2”, “objeto3”] y en el de las diferencias están estos [5, 40, 95], entonces se pasará por pantalla los valores del índice 0 que es donde está el valor mínimo 5, es decir, se mostrará por pantalla “objeto1, 5”.

