```Note

Los arreglos dentro de PHP pueden contener diferentes tipos de datos almacenados en ellos sin ningún problema y se pueden manipular
```
```PHP
<?php

    $calificacion = [100,90,80,88];

    $arreglo = ["cadena", 43, true];

    echo "<pre>";

    print_r($arreglo); //funcion para imprimir los arreglos

    echo "</pre>";

    // etiqueta pre es para preformatear un String

?>
```


**Los objetos en PHP existen cuando hacemos una instancia de una clase**
```PHP
<?php

    Persona = new Persona();
?>
```


# Arreglos asociativos


```PHP
<?php

    $persona = [

        "nombre" => "Daniel",

        "edad" => 25,

        "direccion" => [

            "ciudad" => "Milpa ALta",

            "pueblo" => "San Juan"

        ],

        "calificaciones" => [100,70,65,67]

    ];

    echo "<pre>";

    print_r($persona);

    echo "</pre>";

    echo "<br>";

    print($persona["nombre"]);

    echo "<br>";

    print($persona["direccion"]["pueblo"]);

    echo "<br>";

    print($persona["calificaciones"][1]);

?>
```

![[Pasted image 20230824093339.png]]