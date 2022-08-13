## for
Los bucles for son fragmentos de codigo que podemos ejecutar un determinado numero de veces segun nuestras necesidades. Por ejemplo podemos ejecutar un bucle for tantas veces como elementos tenga un array, o una cadena de texto ... etc

#### Principalmente tenemos dos maneras de declarar sentenicias for

1. Estableciendo una variable que ira incrementando su valor y estableciendo un limite.
```js
for (let i = 0; i < 1000; i++){
	//Codigo a ejecutar
}
```
En este ejemplo estamos declarando una variable, seguido de la condicion que se tiene que cumplir para que el ciclo se ejecute , finalmente, incrementamos la variable en cada ciclo.

2. Directamente especificando con `in`  o `of` que queremos que se ejecute tantas veces como elementos hay en un iterable.


```js
const array = [1, 3, 5, 9];

for (indexOfElement in array){
	//Codigo a ejecutar
}

for (element of array){
	//Codigo a ejecutar
}
```

## And,  Or, not

Estos son operadores logicos y nos sirven para trabajar con valores booleanos.

#### and `&&`
Este nos sirve para adjuntar otras condiciones que deben de cumplirse para que expresion de true

#### or `||`
Nos sirve para especificar que si alguna de las condiciones se cumple devuelva true.

#### not `!`
Con `not` podemos invertir un booleano. Es decir un true cambiarlo por un false y viceversa
Tambien podemos utilizarlo para indicar 'No es igual' con `!==` para especificar que si dos valores no son iguales devuelva true

##### Ejemplo
```js
if ('hola' !== 'chao'){
	//Codigo a ejecutar
}
```
En este ejemplo el codigo de adentro se ejecutara dado que la expresion esta devolviendo true por que los dos operandos son distintos.