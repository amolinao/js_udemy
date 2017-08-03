Javascript no es Asíncrono.

Al cargar la página y ver la consola, comienza un contador que imprime 8000 veces la palabra imprimió.

Si mientras esto ocurre se pulsa el botón que muestra en consola "se pulsó botón" esto no es mostrado
hasta que no se pintan las 8000 veces la palabra. Es decir hasta que no finaliza la primera función.

Esto es así porque el lenguaje tiene una pila de funciones y no comienza la siguiente hasta no haber finalizado
la actual. (no es Asíncrono)

