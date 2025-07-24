En la terminal se puede guardar una variable.
Por ejemplo `myname="Martin"`.
Para imprimir el valor de la variable se debe ejecutar `echo $myname`.

En el script siempre se debería usar doble comillas para que se imprima el valor de la variable y no el nombre de la variable (caso de usar comilla simple). Además, al tener un apóstrofe también generaría conflicto en el comando `echo`.

Otro uso de las variables es almacenar la salida de un comando. Por ejemplo `files=$(ls)`.

En la terminal se pueden escribir comandos en serie mediante `&&`. Por ejemplo, `files=$(pwd) && echo $files`.

Las variables con mayúsculas son las que vienen por defecto con el sistema.
Se pueden crear variables con mayúsculas pero no sería una buena práctica.
Para conocer las variables, se puede ejecutar el comando `env`.