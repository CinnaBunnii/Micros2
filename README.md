# Descripción
- El ADC tiene una resolucion igual a 10 bits.
- Es de aprozimacioens sucesivas.

![](https://cdn-reichelt.de/bilder/web/xxl_ws/B300/ARDUINO_UNO_A06.png)


# EXAMEN INSTITUCIONAL DE MICROCONTROLADORES.
## NOMBRE: Karla Denisse Zambrano Barrientos
Instrucciones: Contestar las siguientes preguntas y enviar el archivo en PDF en TEAMS, donde vendrá una carpeta llamada INSTITUCIONAL, fecha límite jueves 8 de agosto antes de las 23:59.
#### Sección 1
1.	¿Cuántos puertos tiene el microcontrolador ATMEGA328P? 
  - a.	3 (PORTB, PORTC, PORTD).
2.	¿Cuál es la diferencia entre el microcontrolador y la tarjeta de desarrollo Arduino?
- a.	El Arduino tienen un microcontrolador integrado en su base, junto a pines y otros componentes donde se facilita las operaciones y la programación del microcontrolador con su software. Mientras el microcontrolador por sí solo esta más limitado en sus instrucciones y operaciones, y es mas complejo cuando se trata en codificar. 
3.	¿Cuántos volts entrega cada pin de los puertos?
- a.	5V.
4.	¿Cuánta corriente entrega cada uno de los pines de los puertos del microcontrolador?
- a.	40mA máximo
5.	Se necesita conectar dos LEDs, para lo cual se van a utilizar los pines 0 (cero) y 7 (siete) del microcontrolador (PUERTO D), escribe el numero en binario y hexadecimal que se le tiene que escribir al puerto para encenderlos.
- a.	Binario: PORTD = 0B10000001;
b.	Hexadecimal = PORTD = 0x81
6.	¿Qué es una localidad de memoria en el microcontrolador?
- a.	Es donde se almacenan los datos del microcontrolador.
7.	¿Cuál es la capacidad del microcontrolador para la memoria de programa?
- a.	Puede tener entre 2 Kb hasta 512 Kb dependiendo del microcontrolador. El ATMEGA328P tiene 32 Kb.
8.	¿Cuál es la capacidad del microcontrolador para la memoria de datos?
- a.	2 Kb.
9.	¿Cuál es la diferencia entre la arquitectura Harvard y Von Newmann?
- a.	En la arquitectura Harvard los datos son almacenados en dos memorias: una para el programa e instrucciones y la otra para los restos de los datos. 
- b.	En la arquitectura Von Newmann todo es almacenado en un mismo lugar.
10.	¿De cuantos bits es el microcontrolador ATMEGA328P?
- a.	8 bits
11.	¿De cuantos bits es el ADC del microcontrolador?
- a.	10 bits
#### Sección 2
Responde cierto o falso.
12.	Se requiere controlar un motor DC, para lo cual se debe conectar directamente el motor a la tarjeta Arduino UNO para hacerlo funcionar.

-  FALSO

13.	Necesito conectar un LED a la tarjeta Arduino UNO, ¿es necesario forzosamente poner una resistencia a tierra? 
- SI : para que no se queme      

14.	Describe los comandos del git flow básico para subir archivos al repositorio de GIT.
- a.	$ pwd: imprime el directorio de trabajo actual, lo cual nos ayuda para entrar a nuestro disco local y localizar nuestros archivos.
- b.	$ cd ..: nos permite movernos entre los directorios y localizar nuestros archivos en el disco local.
- c.	$ cd ..:
- d.	$ cd “nombre de carpeta”: hemos llegado a la carpeta que utilizaremos y que contiene los archivos que subiremos al repositorio.
- e.	$ git add “nombre de archivo” : aquí escogemos el archivo que vamos a subir.
- f.	$ git commit -m “  “: podemos agregar un comentario o mensaje con este comando
- g.	$ git push origin master: Ya subimos nuestro archivo al repositorio. 

#### Sección 3
Reflexiona y responde las siguientes preguntas.
1.	Que es una señal.
- a.	Es una magnitud de naturales que puede ser medida y procesada. 
2.	¿Sería posible procesar una señal sin recurrir al muestreo?
- a.	No, es el primer paso para procesar señales, y sin ella, no se le puede asignar un valor a nuestra señal. 
3.	¿Porque se debe muestrear una señal?
- a.	Para poder tener una visualización o colocarle un valor a la señal. Así podremos saber con lo que estamos trabajando y tener medidas exactas que nos ayudaran para entender más nuestras situaciones o trabajos. 
4.	¿Cómo relacionas el tamaño de paso del microcontrolador con los números binarios?
- a.	El tamaño de paso indica que tan buena será la resolución de un microcontrolador, y los números binarios demuestran de forma digital esa conversión de resolución. 
5.	¿Cuál crees que sea la diferencia entre lo análogo y lo digital?
- a.	Lo analógico es continuo y pueden tomar cualquier valor, mientras el binario simplemente solo puede tener dos valores, siendo el 1 o 2. 
