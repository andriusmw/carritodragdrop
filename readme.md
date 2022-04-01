# Kata Carrito de Compra con funcionalidad Drag & Drop en JavaScript

Este proyecto ha sido trasladado de su repositorio original para una mejor presentación, si quieren ver los commits realizados 
para crear el proyecto originalmente, vayan al enlace: https://github.com/andriusmw/BOOTCAMP-2022/tree/master/katas/kata%20carrito%20drag%20and%20drop 

Bootcamp2022 --> katas --> kata carrito drag and drop

Este proyecto muestra un menú de compra y un carrito, cuando arrastramos elementos del menú de compra
al carrito, se genera un div dentro del carrito, con el nombre y precio del elemento arrastrado, así mismo
se añade el precio del item al array listaprecios y al array preciosaborrar, para más adelante 1-poder calcular
el total a pagar sumando los valores del primer array y 2- poder borrar elementos del carrito borrando el objeto del
array preciosaborrar que coincida con el precio que hemos eliminado y así obtenemos un índice para pasarle a la función
de borrar precios del array listaprecios y borrar el precio del total 

(lo borramos "3 veces", primero eliminamos la parte visual, de los divs y demás, luego borramos el precio del array de preciosaborrar
y después al haberlo borrado de ese array, tenemos la información necesaria para poder borrarlo del array de precios a calcular el total)


## Comenzando 🚀

Para hacer funcionart este proyecto solo hay que descargarlo y abrirlo con un navegador compatible con JavaScript.




## Ejecutando las pruebas ⚙️

La aplicación consta con varios console.log() para saber el estado de las cantidades a cobrar en cada momento, de esa manera;
nos muestra por consola el contenido del array listaprecios cada vez que se añade un elemento al carrito, eso sería lo que después sumaría
cuando le demos al botón de sumar. 

Se puede comprobar que borra elementos, cuando le damos al botón de X en su fila a un elemento. No solo desaparece visualmente;
sino que por consola se nos muestra el estado del array de precios a borrar antes y después de borrar.

Y si volvemos a calcular el total a pagar en ese momento con los artículos restantes, así lo hará y nos mopstrará por consola de nuevo
antes de sumar el contenido del array listaprecios; que corresponde con los elementos a sumar para pagar.


## Construido con 🛠️

-Visual Studio Code
Empleando html5,css y JavaScript



## Autores ✒️

Andrius MW Front End Web Developer


## Expresiones de Gratitud 🎁

Youtube y San Google.