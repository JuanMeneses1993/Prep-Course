## Variables
Podemos decir que una variable como una cajita que pude contener un lo que nosotros querramos. Esta cajita posee un nombre con el cual la podemos invocar cada vez que necesitamos utilizar su contenido. 

Una explicacion mas tecnica del tema es que es una asignacion de memoria a la cual le hemos puesto un nombre cuyo contenido podemos acceder, modificar o incluso realizar operaciones con el.

## Maneras de declarar variables

### Var
Esta actualmente es poco utilizada debido a las ventajas que ofrecen let y const. Y su principal diferencia es que tiene un scope o alcanze de funcion es decir que puede ser accedida en cualquier parte de la funcion

### Let
Esta se utiliza para declarar variables con un alcanze de bloque. Es decir su uso esta limitado a los corchetes dentro de los cuales se encuentre contenida. Fuera de los corchetes mas proximos no puede ser accedida

### Const
Esta presente las mismas caracteristicas en cuanto a su alcance que let, su unica diferencia es que se utiliza para declarar constantes.



## Strings 

Cadenas de caracteres. Estas son secuencias de digitos alfanumericos y de simbolos encerrados en comillas bien sea simples o dobles. Estas son considerados como valores primitivos ya que son los valores mas basicos que existen dentro de javascript junto con los booleans, numbers, Null, Undefines y Sign 
## Funciones (argumentos, return)

Las funciones son piezas de codigo aislado al cual le podemos asignar un nombre, podemos utilizarlas  cuando las necesitemos sin necesidad de volver a escribirlas. Solo con llamar a dicha pieza de codigo podemos hacer que se ejecute el codigo que esta contenido en ellas. 

Dichas piezas de codigo pueden o no tener entrada de valores(Tambien llamados argumentos o parametros), estos valores pueden variar cada vez que deseemos  y el codigo de la funcion se ejecutara con los valores que le pasemos en ese momento dado

Las funciones siempre devuelven un valor. Esto nos sirve para utilizar fuera de la funcion los resultados que nos halla dado la funcion. Aunque tambien podemos omitir la devolucion de un valor y por defecto devolvera Undefined. Para retornar estos valores tenemos la palabra reservada Return La cual detiene la ejecucion de la funcion instantaneamente sin importar en que parte de la funcion este y devuelve el valor que le pasemos

## Manera de declarar una funcion
### Funcion tradicional
Para declarar una funcion de la manera tradicional basta con utilizar la palabra reservada `function` seguido del nombre de la funcion y unos parentesis donde declararemos los parametros de ser necesarios para la ejecucion de la funcion luego tenemos entre corchetes el cuerpo de la funcion que contendra el codigo que esta funcion debe de ejecutar.

##### Ejemplo
```js
function miFuncion(){
	//Codigo de la funcion
}
```
### Funcion flecha

Este tipo de funcion normalmente la guardamos dentro de una variable o la pasamos directamente como parametro de otra funcion.

Esta comienza con los parametros de necesitarlos encerrados entre parentesis. seguido de => y despues el codigo encerrado entre corchetes ( si es una sola expresion no es necesario el uso de los corchetes. )

##### Ejemplo

```js
var mifuncion = ()=>{ // Aqui va el codigo}
```
## Funcion Anonima
Este tipo de funcion tambien la podemos asignar a una variable o pasarla como parametro, y podemos saltarnos si lo deseamos de declararla con un nombre

##### Ejemplo
```js
var mifuncion = function( ) {

	// Aqui el codigo de la funcion
}
```


## Llamado de funcion

Para llamar una funcion previamente declarada basta con que utilizemos su nombre seguido de parentesis que contengan los parametros si esta los utiliza

##### Ejemplo
```js
miFuncion()
```
## Declaraciones if

Los if son utilizados cuando queremos que un fragmento de codigo se ejecute solo si una condicion se cumple. Estos evaluan una expresion si la expresion es true ejecuta el codigo de lo contrario lo ignora.

## Valores booleanos

Estos son valores que tienen solo dos posibles estados. true o false.