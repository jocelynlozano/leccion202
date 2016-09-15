Solución de Ejercicios  
======================
###Closures

#####Modificar el siguiente script usando closures para que se ejecute sin problemas.

-En la imágen 1 se puede notar que hay una variable local declarada dentro de la función la cual tienen el mismo nombre que la variable global. Cuando el interprete de javaScript revisa línea por línea, llega a un momento en donde lee la condición, la cual busca una variable, y como se sabe, si la variable local lleva el mismo nombre que la variable global, la primera predomina, es decir la variable local tiene más peso que la global. La condición sabe que hay una variable local por ello se enfoca en ella pero como aún no está iniciada la declara como "Undefined" por esto la condición es "True" entonces pasa a leerla.

![alt text](http://es.tinypic.com/r/ncij46/9)

-En la imagén 2 se puede notar que solo hay una sola variable, la cual es la variable global y como ya tiene un valor de tipo "string" al pasar por la condición la igualdad es "false", por ello bota la respuesta correcta.

