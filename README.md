
# Bipolar Stepper Motor

También llamado Motor paso a paso,es un motor de corriente contínua sin escobillas que divide una rotación completa en varios pasos iguales.

La posición del motor se puede dirigir para que se mueva y se mantenga en uno de estos pasos sin ningún sensor de posición	 para la retroalimentación (un controlador de bucle abierto). Los motores paso a paso bipolares son un tipo de motor  con un único bobinado por fase y sin toma centrarl (A diferencia de un motor paso a paso unipolar).



![Diferencias](https://imgur.com/IyUVM0Q.jpg)

![Diferencias2](https://imgur.com/G3XjpXq.jpg)
## Como usar en pico

![Esquema](https://imgur.com/9H5Agrr.jpg)

El siguiente esquema propone una forma de uso para complementar la explicación de la función del motor paso a paso.
Consta de estar conectado a las salidas gpi, con 4 botones que cada una tiene una instrucción para el motor:
* Girar en sentido horario
* Girar en sentido antihorario
* Aumentar/disminuir velocidad
* Cambiar secuencia del motor(1 paso, 2 pasos o medio paso)
