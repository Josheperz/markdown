# Guia de markDown 

## Encabezados

Existen 6 niveles de prioridad al igual que en HTML. En lugar de definirlos con un numero (1-6) precedido de la h, en markDown el numeral-hasts-almuadilla colocando antes del texto y seguido de un espacio , determinara el nivel de prioridad del encabezado.

    # Encabezado 1
    ## Encabezado 2
    ### Encabezado 3
    #### Encabezado 4
    ##### Encabezado 5
    ###### Encabezado 6
    
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6


## Citas

Para escribir citas solo debemos colocar al inicio del parrafo el simbolo mayor que ">". si querenos hacer un salto de linea, lo realizamos y aun la siquiente linea seguira formando parte de la cita pero si damos dos saltos de linea el siguiente texto ya no formara parte de la cita
## Ejemplo:
~~~
  > El MarkDown es un
  lenguaje de marcado ligero.
~~~
> El MarkDown es un
lenguaje de marcado ligero.

## Listas Desordenadas

Solo requiere colocar un guion al inicio del elemento que vamos a listar seguido de un espacio y sin mas sera reconocido como una elemento de lista.

Algunos aplicaciones reconocen el signo de + ; *  al igual que el guion - y marcan el elemento como una lista.
~~~
- Elemento 1     
+ Elemento 2    
* Elemento 3 
~~~
- Elemento 1     
+ Elemento 2    
* Elemento 3 

## Lista Numerada

Si en cambio que deseamos hacer una lista numerada, solo debemos anteponer el numero seguido de un punto y un espacio antes de comenzar a escribir y listo.
~~~
1. Elemento 1
2. Elemento 2
3. Elemento 3
~~~
1. Elemento 1
2. Elemento 2
3. Elemento 3

Para anidar listas desordenadas dentro de listas numeradas so lo debes añadir un espacio con tabulador y colocar la siguiente lista.
~~~
1. Elemento 1     
2. Elemento 2    
3. Elemento 3     
  - Elemento 1          
  - Elemento 2          
  - Elemento 3          
~~~
1. Elemento 1     
2. Elemento 2    
3. Elemento 3     
  - Elemento 1          
  - Elemento 2          
  - Elemento 3 
 
## Separaciones

Lo que en HTML seria la etiqueta \<hr>, para colocar una separacion, en markDown se colocan tres guiones bajos para obtener ese resultado.

___

## Negrita y Cursiva

Para resaltar un texto con negritas solo debemos colocar al inicio antes de comenzar a escribir 2 anteriscos  "**" y al final del texto. si lo que queremos hacer es que el texto o parte de el sea en cursibas solo demebos colocar un * al inici del texto y otro al finalizar.
~~~
"El **MarkDown**  trata de *conseguir* la maxima ***legibilidad y facilidad*** de publicacion tanto en su forma de entrada como de salida."
~~~

"El **MarkDown**  trata de *conseguir* la maxima ***legibilidad y facilidad*** de publicacion tanto en su forma de entrada como de salida."

Como podemos notar en el ejemplo anterior, cuando queremos que el texto sea en negritas y cursiva solo debemos colocar 3 anteriscos ***antes del texto deseado y al finalizar***

## Enlaces

La palabra que vamos a utilizar como texto ancla debe ir entre corchetes [ ] y la direccion url entre parentesis (), si dentro del parentesis luego de colocar la url escribo entre comillas una frase, esta se convertira en el title de ese enlace.
~~~
[Google](https://www.google.com/ "Pagina de Google")
~~~

[Google](https://www.google.com/ "Pagina de Google")

Si queremos que la url sea el enlace, basta con colocarla entre los simbolos mayor que y menor que "<>"
~~~
<www.google.com>
~~~
<www.google.com>




