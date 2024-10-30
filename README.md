# TrabajoDeConsulta - Pedro Yépez
## Funciones SIN nombre
Las funciones SIN nombre, también son conocidas por los nombres funciones anónimas, funciones literales, expresiones lambda.

Se las identifica por no tener un identificador con el que llamarlas

Estas se usan ejecutar ordenes y operaciones sencillas, generalmente de una sola linea

## Por ejemplo: 

val f1 = (n: Int) => n*2

val f2 = (n: Int) => n*n

val f3 = (n: Int) => (1 to n).sum


val numeros = List(1, 2, 3, 4)
val cuadrados = numeros.map(x => x * x)
// Resultado: List(1, 4, 9, 16)
