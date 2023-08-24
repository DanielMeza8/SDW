```NOTE

Con la sentencia for podemos acceder o iterar un arreglo mientras que una condición se cumpla.

```
```PHP
<?php

    $calificacion = [100,90,80,88];  

    $arreglo = ["cadena", 43, true]; 

    for ($i=0; $i < count($calificacion) ; $i++) {

        print($i);

        print($calificacion[$i]);

        echo "<br>";

    }  

	echo "<br>";  

    for ($i=0; $i < count($arreglo) ; $i++) {

        print($arreglo[$i]);

        echo "<br>";

    }
?>
```
