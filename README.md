# SPD_Luca_Gargiulo_1D
PARTE 1:
Componentes: boton aumentar, boton disminuir, boton reset, display decena, display unidad
Si toco el boton aumentar, suma 1
Si toco el boton disminuir,  resta 1
Si toco el boton reset, vuelve a 0
Funciones:
funciones de mostrar 0,1,2,3,4,5,6,7,8,9,(encienden o apagan los segmentos del display),
presionarTecla(detecta la tecla presionada)
prenderDigito(controla el encendido y apagado de dos digitos(unidad y decena) en los display, se pasa el numero por parametro),
printDigit(muestra un digito en un display, dependiendo el numero pasado por parametro)
printCount(muestra un numero en un display de 2 digitos, pueden ser todos los numeros o solo los primos, dependiendo el numero y el estado del deslizante pasados por parametro)

PARTE 2:
Componentes: boton aumentar, boton disminuir, boton deslizante(numeros, solo primos), motor cc, display decena, display unidad
Si el boton deslizante esta encendido, en el display se van a mostrar todos los numeros del 0 al 99, (si tocas el boton aumentar, suma 1, si tocas el boton disminuir, resta 1)
Si el boton deslizante esta apagado, en el display se van a mostrar solo los numeros primos del cero al 99 (si tocas el boton aumentar, busca el siguiente numero primo, si tocas el boton disminuir, busca el anterior primo)
Si el  boton deslizante esta en el modo normal(todos los numeros), el motor cc va a girar a la derecha si el numero es primo, si no es primo, el motor gira a la izquierda
Si el boton deslizante esta en modo numeros primos(solo primos), el motor se queda apagado
Funciones: 
funciones de mostrar 0,1,2,3,4,5,6,7,8,9,(encienden o apagan los segmentos del display),
presionarTecla(detecta la tecla presionada)
prenderDigito(controla el encendido y apagado de dos digitos(unidad y decena) en los display, se pasa el numero por parametro),
printDigit(muestra un digito en un display, dependiendo el numero pasado por parametro)
printCount(muestra un numero en un display de 2 digitos, pueden ser todos los numeros o solo los primos, dependiendo el numero y el estado del deslizante pasados por parametro)
encenderMotorDerecha, 
encenderMotorIzquierda, 
apagarMotor, 
esPrimo(determina si un numero es primo, recibe un numero como parametro, devuelve true or false),
siguientePrimo(busca el proximo primo a partir del numero pasado por parametro, devuelve un entero),
anteriorPrimo(busca el anterior primo a partir del numero pasado por parametro, devuelve un entero),


PARTE 3:
