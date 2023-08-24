
```NOTE
Nos permite ejecutar un bloque de código si una condición se cumple o no
```


Ejemplo de como usar if-else en nuestro programa
```PHP
<?php
    $edad = 65;  

    if ($edad >= 18 & $edad < 30) {

        printf("Es mayor de edad");

    } else if ($edad >= 30 & $edad < 60){

        printf("Es un adulto joven");

    } else if ($edad >= 60){

        printf("Es un adulto mayor");

    } else {

        printf("Eres menor de edad");

    }  
?>
```

*Ejemplo de como usar switch en nuestro programa*

```NOTE
	En la sentencia switch, esta nos sirve para definir si nuestra variable hace match con alguno de nuestros casos dentro del switch este fragmento de codigo sera ejecutado segun cual sea el que corresponda
```

```PHP
<?php

    $opcion = "HTML";
    switch ($opcion){

        case 'HTML':

            print("lenguaje de maquetado");

            break;

        case 'CSS':

            print("lenguaje de progrmacion de estilos");

            break;

        case 'JS':

            print("lenguaje de programacion cliente");

            break;

        default:

            print("Esta opcion no existe");

            break;
    } 

?>
```


