# Proyecto-Integral Lampara Marc
vamos a crear un proyecto con lampara 

emepezaremos con un proyecto integrado llamado lampara  

* Me gustaría hacer una lámpara fluorescentes, no conozco ninguna lámpara similar que yo quiera imitar, de momento ningún cambio quiero hacer así está bien por ahora.

* El proyecto de lámpara consistirá en una lámpara led programada por Arduino y consistirá de las siguientes partes.
Pantalla y forma de la lámpara donde se colocará el/el LED.
Mecanismo de apagado y encendido de la luz LED. (interruptor)
Pieza para ocultar el Arduino que se podrá desconectar para reutilizarlo.
Programación del Arduino

* Sobre el tipo de bombilla
* ¿Cuántos leds va a tener mi lámpara? ¿Van a ser de uno o de varios colores? Mi lampara va a tener 3 leds, van a ser de varios colores.

*Sobre la pantalla y el soporte
*
En la lámpara que vas a hacer ¿se ve directamente el led? ¿Queda tapado a través de una pantalla semitransparente o un difusor?
¿La lámpara tiene alguna forma en concreto? (por ejemplo, la lámpara con forma de dragón que quiere hacer Marcos)
¿De qué material y de qué color imaginas todo? ¿Podemos hacer alguna de las piezas con láser/fresado/impresión 3D? (cuanto más se pueda fabricar, mejor)

* ¿se ve directamente el led? ¿Queda tapado a través de una pantalla semitransparente o un difusor? No se ve directamente queda tapado a través de una pantalla semitransparente.
* ¿La lámpara tiene alguna forma en concreto? Si tiene forma circular
* ¿De qué material y de qué color imaginas todo? ¿Podemos hacer alguna de las piezas con láser/fresado/impresión 3D? (cuanto más se pueda fabricar, mejor)
Cable portalámparas con enchufe lo imagino todo así

* ¿podemos hacer alguna de las piezas con láser/fresado/impresión 3D? (cuanto más se pueda fabricar, mejor)
si podría hacer con impresión 3D fresado o láser con alguna de esas 3. Depende del material si resiste mejor será mejor si no resiste mucho no será bueno el material.

Sobre la pieza donde estará inserto el Arduino.
Esto se va a unir a un Arduino
* ¿cuánto de largos han de ser los cables que unan al Arduino?
14.6 x 11 x 1 cm el cable macho por ejemplo mediría esto.

* ¿Cómo es esa pieza que se inserta? Casquillos es la pieza que se inserta

* ¿De qué material es? Fiamateacero, bronce o plástico.

* ¿podemos hacer alguna de las piezas con láser/fresado/impresión 3D? (cuanto más se pueda fabricar, mejor)
si, se podría hacer con impresión 3D, fresado y láser.

* ¿Por dónde entra el cable/los cables que sean necesarios para alimentar el Arduino? Se necesita un cable que este conectado a los 5v  y otro cable que esté conectado a vin 2v  y listo.

Sobre el mecanismo
* ¿Qué tipo de activación tiene el LED?
El LED se activa y se desactiva de forma automática, pero Además, se pueden utilizar también los procedimientos siguientes para activar y desactivar el LED.

* ¿qué modos de funcionamiento tiene?
A diferencia de la lámpara de incandescencia cuyo funcionamiento es por una determinada tensión, el Led funcionan por la corriente que los atraviesa. Su conexión a una fuente de tensión constante debe estar protegida por una resistencia limitadora, veremos más adelante algunos ejemplos.

* ¿Cómo es físicamente el sistema de activación del led?
*
* ¿es un botón?
*
* ¿es un interruptor de palanca?
* es un interruptor de palanca.
* es un potenciómetro ¿*
* es un detector de movimiento?

* ¿Dónde está la pieza dentro de toda la lámpara? La pieza dentro de toda la lámpara se refiere a la bombilla que se sitúa dentro de toda la lámpara.
Sobre el programa

* ¿Qué tipo de funcionamiento tiene el LED? El led básicamente su funcionamiento poner cualquier código que vaya al Arduino y después montar cualquier circuito que tenga led, botón, resistencia y por supuesto los cables bien conectados una vez hecho esto el funcionamiento del led puede encenderse, parpadear rápido, lento o estar siempre encendido fijamente o estar apagado fijamente.

![foto ciculo lampara ejemplos](https://github.com/marc125678/Proyecto-Lampara/blob/main/circulo%20lampara%20.png)

![](https://github.com/marc125678/Proyecto-Lampara/blob/main/lampara%20en%20negra%20y%20blanca.jpg)

![Lampara de Rey Leon Pelicula de Disney](https://github.com/marc125678/Proyecto-Lampara/blob/main/rey%20leon%20disney%20.jpg)

   este es el logo de ncs hecho en inkscape
![este esl logo de ncs](https://raw.githubusercontent.com/marc125678/Proyecto-Lampara/main/Captura%20de%20pantalla%20de%202021-04-29%2012-39-04.png)

captura de pantalla logo ncs mal hecho intentado en inskcape

![captura de pantalla logo ncs mal hecho intentado en inskcape](https://raw.githubusercontent.com/marc125678/Proyecto-Lampara/main/Captura%20de%20pantalla%20de%202021-04-29%2010-29-16.png)


esta es la imagen de la foto no me funcionaba porque habia puesto los leds de alrevez y varios cables estaban mal puestos
![foto de la lampara](https://raw.githubusercontent.com/marc125678/Proyecto-Lampara/main/IMG_20210430_095948.jpg)
este es el codigo de la imagen de arriba que los 3 leds que tenia alrevez , que la imagen sale un libro o sea la anterior imagen.
![codigo de la imagen de los 3 leds que estaban de alrevez](https://raw.githubusercontent.com/marc125678/Proyecto-Lampara/main/Captura%20de%20pantalla%20de%202021-04-30%2013-19-45.png)
capturas de pantalla potenciometro y 3 leds.
![capturas de pantalla potenciometro y 3 leds](https://raw.githubusercontent.com/marc125678/Proyecto-Lampara/main/Captura%20de%20pantalla%20de%202021-04-30%2012-59-18.png)
![](https://raw.githubusercontent.com/marc125678/Proyecto-Lampara/main/Captura%20de%20pantalla%20de%202021-04-30%2012-59-12.png)
svg logo ncs ![](https://raw.githubusercontent.com/marc125678/Proyecto-Lampara/52fc0bf776493f025f35e5228e8188583da52103/Metacrilato.svg)

he copiado 3 veces el mismo codigo y era solo 1 vez el codigo se llama valorPotencimetro = analogRead(pinPotencimetro); lo mismo pasa con el valorIntensidad = valorPotencimetro/4; que me ha pasado lo mismo lo he copiado 3 veces el mismo codigo y lo tenia que copiar 1 sola vez.

pdf logo ncs ![](https://github.com/marc125678/Proyecto-Lampara/blob/main/Metacrilato.pdf)

caja lamapara svg
![](https://github.com/marc125678/Proyecto-Lampara/blob/main/caja%20lampara.Marcsvg.svg)
https://github.com/marc125678/Proyecto-Lampara/blob/main/proyecto_lampara.ino



cuanto mide de alto? mide 120 de alto 
cuanto mide de ancho? y mide 40 de ancho 

``` C++



const int led1pin = 3;
const int led2pin = 5;
const int led3pin = 6;
const int pinBoton = 2;
const int pinPotenciometro = A0;

int valorPotencimetro= 0;
int valorIntensidad = 0;


int estadoBoton = 0;
int estadoPrevioBoton = 0;

bool encenderLeds = false;

void setup() {
  // declare the LED pins as outputs
  pinMode(led1pin, OUTPUT);
  pinMode(led2pin, OUTPUT);
  pinMode(led3pin, OUTPUT);  

  // declare the switch pin as an input
  pinMode(2, INPUT);
}

void loop() {
 leerBoton();
 leerPotenciometro(); 
 encender();
}

void leerBoton() {
  

  estadoBoton = digitalRead(2);

  if (estadoBoton == HIGH && estadoPrevioBoton == LOW) {
     encenderLeds = !encenderLeds;
  }

  estadoPrevioBoton = estadoBoton;
  
}

void leerPotenciometro()
{
  valorPotencimetro = analogRead(pinPotenciometro);

  valorIntensidad = valorPotencimetro/4;

 
}


void  encender() {
 if(encenderLeds){
  analogWrite(led1pin,valorIntensidad);
  analogWrite(led2pin,valorIntensidad);
  analogWrite(led3pin,valorIntensidad);

 }
 else{
  digitalWrite(led1pin, LOW);
  digitalWrite(led2pin, LOW);
  digitalWrite(led3pin, LOW);
 }
  
}

``` 
