Javascript no es As�ncrono.

Al cargar la p�gina y ver la consola, comienza un contador que imprime 8000 veces la palabra imprimi�.

Si mientras esto ocurre se pulsa el bot�n que muestra en consola "se puls� bot�n" esto no es mostrado
hasta que no se pintan las 8000 veces la palabra. Es decir hasta que no finaliza la primera funci�n.

Esto es as� porque el lenguaje tiene una pila de funciones y no comienza la siguiente hasta no haber finalizado
la actual. (no es As�ncrono)

