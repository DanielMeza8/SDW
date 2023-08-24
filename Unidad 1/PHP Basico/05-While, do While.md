```Note
Una característica de While es que primero evalúa y después ejecuta
Do While nos permite ejecutar un bloque de código siempre que se cumpla una condición, la característica mas relevante es que primero ejecuta y después evalúa.
```

```PHP
<?php

    $a = 11;  

    while ($a <= 10) {

        print($a);

        $a++;

    }

    do {

        print($a);

        $a++;

    } while ($a <= 10);  

?>
```
