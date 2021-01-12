### ANÁLISIS DE MALLAS


### INTEGRANTES: LIZBETH CHANGOLUISA - EDISON CADENA


1. OBJETIVOS

OBJETIVO GENERAL:

* Realizar las mediciones de corrientes y voltajes en un circuito con tres fuentes de poder y comparar los valores obtenidos experimentalmente, con los obtenidos del cálculo aplicando las leyes de Kirchhoff.

* La experiencia de este laboratorio consiste en hacer la configuración en un circuito eléctrico para comprobar experimentalmente el Analisis de Mallas.

OBJETIVOS ESPECÍFICOS: 

* Afianzar experimentalmente las leyes de conservación de la energía eléctrica y la Conservación de la carga a traves de las mallas.

* Verificar las leyes de Kirchhoff: Ley de Mallas, ley de Nodos para econtrar la corriente de cada malla.

2. MARCO TEÓRICO 

* Resumen:

El análisis de mallas es una técnica que hace uso de la LVK para expresar voltajes en
función de corrientes.
Una malla es una trayectoria cerrada que no encierra dentro de sí a ningún elemento del
circuito.

* Introducción:

El método de la corriente de malla es otro método bien organizado para resolver circuitos (el otro es el del voltaje en los nodos). Al igual que en cualquier análisis de circuito, tenemos que resolver un sistema de 2E2E2, E ecuaciones independientes, donde EEE es el número de elementos del circuito. El método de la corriente de malla facilita el análisis, y produce un número relativamente pequeño de ecuaciones a resolver.
El método de la corriente de malla se basa en la ley de voltaje de Kirchhoff (LVK).
El método de la corriente de lazo es una pequeña variación del método de la corriente de malla.

Lazos y mallas:

El método de la corriente de malla utiliza dos términos especiales: lazo y malla.

![](https://github.com/eddy90cg/lab2fce/blob/master/img/circuito%20marco%20teorico.jpg)

Un lazo es cualquier trayectoria cerrada alrededor de un circuito. Para formar un lazo, debes comenzar en la terminal de algún componente y trazar un camino a través de elementos conectados hasta llegar nuevamente al punto de partida. Un lazo solo puede pasar por un elemento una vez (de tal forma que no obtengas lazos que parezcan el número 8). 
 
Una malla es una clase restringida de lazo; una malla es un lazo que no contiene otros lazos. 
En el método de la corriente de malla, usamos las mallas de un circuito para generar las ecuaciones LVK.

Ley de nodos:

 La suma algebraica de las corrientes en un nodo es igual a cero.      

I1 – I2 – I3 = 0

Ley de mallas: 

La suma de todas las caídas de tensión en un malla es igual a la suma de todas las tensiones aplicada

VAB = V1 + V2 + V3


Corriente de lazo: 

Ahora definimos un nuevo término, la corriente de lazo (también las puedes llamar corrientes de malla). Hasta ahora, cuando hemos hablado de corriente, ha sido generalmente en el contexto de una corriente de elemento (la corriente que fluye a través de un elemento del circuito). La corriente de lazo designa una hipotética corriente que fluye exclusivamente alrededor de un lazo. 

Miremos de cerca a R3  en la rama de en medio del circuito. 

![](https://github.com/eddy90cg/lab2fce/blob/master/img/corriente%20lazo%20marco%20teorico.jpg)

De la forma en que están dibujadas las corrientes de lazo, parece que ambas pasan por R3 pero en direcciones opuestas. ¿Puede esto ser verdad? Sí, porque podemos utilizar un concepto muy importante llamado principio de superposición.

El principio de superposición:

La palabra superposición es una manera elegante de decir suma. En el caso de R3 estamos usando el principio de superposición cuando decimos que las corrientes de lazo, i1 e i2 se suman en la corriente existente en el resistor, ir3

+iR3 = +i1 - i2

Las dos corrientes de lazo se superponen (se suman) para formar la corriente a través de R3. 

Linealidad:

La razón por la que podemos usar el principio de superposición con resistores ideales son elementos lineales. La linealidad para un resistor ideal significa que si multiplicamos el voltaje por una constante aaa, entonces la corriente se multiplica por la misma constante a.

v = i . R
av = a.i.R

Existe un límite para el valor de a de un resistor real puede soportar antes de quemarse. Un resistor ideal es un elemento lineal, pues opera para cualquier valor de a.

La linealidad significa que podemos usar el principio de superposición, que a su vez quiere decir que tiene sentido que corrientes de múltiples lazos circulen por un mismo elemento del circuito. Tener varias corrientes significa que podemos utilizar las corrientes de lazo como variables independientes. ¡Y eso implica que podemos utilizar el método de la corriente de lazo para resolver circuitos

Pasos para aplicar el análisis de mallas
Comenzaremos explicando el método para un circuito de 2 mallas. El procedimiento se puede extender luego para circuitos más grandes.
Paso 1
Asignar y dibujar corrientes independientes a cada malla, en este ejemplo son I1 e I2. Se pueden dibujar en sentido horario o también en sentido antihorario.

Paso 2
Aplicar la Ley de las Tensiones de Kirchhoff (LTK) y la ley de Ohm a cada malla. A las caídas de potencial se les asigna signo (-) mientras que a las subidas se les asigna signo (+).

Malla abcda
Partiendo del punto a y siguiendo el sentido de la corriente, encontramos una subida de potencial en el batería E1 (+), luego una caída en R1 (-) y después otra caída en R3 (-).

Simultáneamente, la resistencia R3 es atravesada también por la corriente I2, pero en sentido contrario, por lo tanto representa una subida (+). La primera ecuación queda así:

E1-R1.I1 –R3.I1 + R3.I2 = 0

Enseguida se factoriza y se reagrupan términos:

– (R1+R3)I1 +R3I2 = -E1  (Ecuación 1)

Malla cefdc 
Partiendo del punto e y siguiendo el sentido de la corriente se encuentra una caída de potencial en R2 (-), otra caída en E2, ya que la corriente entra por el polo + de la batería y finalmente otra caída en R3 (-), Al mismo tiempo la corriente I1 atraviesa R3 en sentido contrario (+).

La segunda ecuación, con los signos indicados, queda de esta forma:

– R2 I2 – E2 –R3 I2 +R3 I1=0

R3I1 – (R2 +R3) I2 = E2  (Ecuación 2)

Nótese que se tienen dos ecuaciones con las dos incógnitas I1 e I2.

Paso 3
Seguidamente se resuelve el sistema de ecuaciones así formado.
 

3. DIAGRAMAS


* Figura, Circuito Teórico para el análisis de mallas:

![](https://github.com/eddy90cg/lab2fce/blob/master/img/circuito%20teorico.jpg)





* Circuito Experimental y simulado para el analisis de malla, medidos con multímetro respectivo a la corrriente de cada malla:

![](https://github.com/eddy90cg/lab2fce/blob/master/img/circuito%20experimental%20y%20simulado.jpg)






4. LISTA DE COMPONENTES

Lista de Materiales y componetes necesarios para desarrollar el circuito expirementalmente y simularlo:

![](https://github.com/eddy90cg/lab2fce/blob/master/img/materiales%20o%20equipo.jpg)

5. EXPLICACIÓN

* Implemente el circuito que se presenta en la figura.

* Mida cada una de las corrientes de malla y anote los resultados en la tabla.

* Simule en el software Multisim, Proteus, o cualquier otro simulador, el circuito
de la figura, en este caso es simulado con el software tinkercad obteniendo los valores de las corrientes de malla. Anote los resultados
en la tabla.

* Compare los valores de la tabla  y realice sus respectivas conclusiones.




6. APORTACIONES

Tabla de Registro de datos tomandos del Experimento:

![](           )

Para poder econtrar los valores de la corriente para cada malla se aplicaron los sigueintes calulos:

![](           )



7. CONCLUSIONES

* Costatamos que las leyes de Kirchhoff al acatar los valores adquiridos tanto de forma teórica como de forma experimental, visulizando que la diferencia entre estas es mínima, por lo tanto podríamos concluir en que las leyes de Kirchhoff se cumplen los valores arrojados de error porcentual de medición del teórico con respecto al experimental depende del instrumento (Resistencia interna,Precisión de medición).

* Los valores de corriente fueron también determinados a partir del método de mallas, y al tener nuestras ecuaciones con la ayuda matrices pudimos obtener los valores teóricos de la corriente y por ende los voltajes, además y se puede apreciar que los valores casi son los mismos.

-A las corrientes de lazo o corrientes de malla se les puede asignar una dirección arbitraria.

-A cada malla esencial –o “ventana”- que tenga el circuito debe asignársele una corriente.

-Las corrientes de malla se denotan con mayúscula para distinguirlas de las corrientes que circulan por ramas, aunque en algunos casos la corriente que circula por una rama puede la misma que la de malla.

8. BIBLIOGRAFÍA

Rodríguez, H. (19 de Octubre de 2017). lifeder. Obtenido de

     https://www.lifeder.com/leyes-kirchhoff/

Pérez, A. (12 de enero de 2015). Electrónica Completa. Obtenido de

     https://electronicacompleta.com/leyes-de-kirchhoff/
     
9. Anexos

