# SPD_Luca_Gargiulo_1D
PARTE 1: 
LINK DE TINKERCAD: https://www.tinkercad.com/things/4cmYyxcN2C1-parcial-parte-1-luca-gargiulo-1-d/editel?sharecode=yVv1DsvqzKNOOr443XenoSYA6DCw0Q7y8clRyKv1es8

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
LINK DE TINKERCAD: https://www.tinkercad.com/things/7gidDRggglA-parcial-parte-2-con-motor-cc-y-sensor-de-tmp-luca-gargiulo-1-d/editel?sharecode=zk_xddD4kh23IgKTQ4-U7LGQdPfFjIrFeFLuB23ukfY

Componentes: boton aumentar, boton disminuir, boton deslizante(numeros, solo primos), motor cc, display decena, display unidad, motor cc, sensor de temperatura,

Si el boton deslizante esta encendido, en el display se van a mostrar todos los numeros del 0 al 99, (si tocas el boton aumentar, suma 1, si tocas el boton disminuir, resta 1)
Si el boton deslizante esta apagado, en el display se van a mostrar solo los numeros primos del cero al 99 (si tocas el boton aumentar, busca el siguiente numero primo, si tocas el boton disminuir, busca el anterior primo)
Si el  boton deslizante esta en el modo normal(todos los numeros), el motor cc va a girar a la derecha si el numero es primo, si no es primo, el motor gira a la izquierda
Si el boton deslizante esta en modo numeros primos(solo primos), el motor se queda apagado
Si el boton deslizante esta en modo normal, tenes la opcion de usar el sensor de temperatura, si el sensor de temperatura es 24 o menos, no hace nada, en cambio si el lo vamos modificando arriza de 24 grados, se van a mostrar en los display 

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
leerTemperatura(lee la temperatura segun el estado del sensor, usa la funcion map y devuelve un entero(temperatura)),


PARTE 3:
LINK DE TINKERCAD: https://www.tinkercad.com/things/4oZK3KYrTs3-parcial-parte-3-sensor-de-luz-ambiental-luca-gargiulo-1-d/editel?sharecode=9-DJo2B7plnt27dQN4dKdjio1Z5inYp-adoV8Fudg5A

Incluye todo lo de la parte 2 y se le agrega:
componentes: Sensor de luz ambiental, Lampara,

Si el boton deslizante esta en modo normal, va a funcionar el sensor de luz ambiental, si el nivel de luz del sensor es menor a 50 se va a encender la lampara y el motor, caso contrario la lampara va a estar apagada y el motor tambien
Si el boton deslizante esta en modo numeros primos, no se va a poder usar,

PARTE 4:
LINK DE TINKERCAD: https://www.tinkercad.com/things/2JY3KU5WzPx-copy-of-parcial-parte-3-sensor-de-luz-ambiental-luca-gargiulo-1/editel?sharecode=nqXgFSmvrjjKYhETAqJA6PH-VVPparqlM0WQkwSq2aM

cambia el deslizante en modo primos, por impares
