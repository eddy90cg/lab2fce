### ANÁLISIS DE MALLAS


### INTEGRANTES: LIZBETH CHANGOLUISA - EDISON CADENA


1. OBJETIVOS

* Comprobar experimentalmente el Analisis de Mallas.

* Econtrar la corriente enn cada malla aplicando leyes de nodo en mallas y leyes de kirchoff.

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

Corriente de lazo: 

Ahora definimos un nuevo término, la corriente de lazo (también las puedes llamar corrientes de malla). Hasta ahora, cuando hemos hablado de corriente, ha sido generalmente en el contexto de una corriente de elemento (la corriente que fluye a través de un elemento del circuito). La corriente de lazo designa una hipotética corriente que fluye exclusivamente alrededor de un lazo. 

Miremos de cerca a \text R3R3start text, R, end text, 3 en la rama de en medio del circuito. ¿Cuál es la corriente que fluye por \text R3R3start text, R, end text, 3?

![](https://github.com/eddy90cg/lab2fce/blob/master/img/corriente%20lazo%20marco%20teorico.jpg)

De la forma en que están dibujadas las corrientes de lazo, parece que ambas pasan por \text R3R3start text, R, end text, 3, pero en direcciones opuestas. ¿Puede esto ser verdad? Sí, porque podemos utilizar un concepto muy importante llamado principio de superposición.

El principio de superposición
La palabra superposición es una manera elegante de decir suma. En el caso de \text R3R3start text, R, end text, 3, estamos usando el principio de superposición cuando decimos que las corrientes de lazo, i_{\text I}i 
I
​	
 i, start subscript, start text, I, end text, end subscript e i_{\text{II}}i 
II
​	
 i, start subscript, start text, I, I, end text, end subscript, se suman en la corriente existente en el resistor, i_{\text R3}i 
R3
​	
 i, start subscript, start text, R, end text, 3, end subscript.
+i_{\text R3} = +i_{\text I} - i_{\text{II}}+i 
R3
​	
 =+i 
I
​	
 −i 
II
​	
 plus, i, start subscript, start text, R, end text, 3, end subscript, equals, plus, i, start subscript, start text, I, end text, end subscript, minus, i, start subscript, start text, I, I, end text, end subscript
Las dos corrientes de lazo se superponen (se suman) para formar la corriente a través de \text R3R3start text, R, end text, 3. La flecha para la corriente de lazo i_ {\text I}i 
I
​	
 i, start subscript, start text, I, end text, end subscript apunta en el mismo sentido que la corriente en la rama i_ {\text R3}i 
R3
​	
 i, start subscript, start text, R, end text, 3, end subscript, dándole un ++plus en la ecuación de superposición. La flecha para la corriente de lazo i_ {\text{II}}i 
II
​	
 i, start subscript, start text, I, I, end text, end subscript apunta en sentido opuesto, por lo que adopta un signo -−minus en la ecuación.

Linealidad:

La razón por la que podemos usar el principio de superposición con resistores ideales son elementos lineales. La linealidad para un resistor ideal significa que si multiplicamos el voltaje por una constante aaa, entonces la corriente se multiplica por la misma constante aaa.
v = i\,\text Rv=iRv, equals, i, start text, R, end text
a\,v = a\,i\,\text Rav=aiRa, v, equals, a, i, start text, R, end text
Existe un límite para el valor de aaa de un resistor real puede soportar antes de quemarse. Un resistor ideal es un elemento lineal, pues opera para cualquier valor de aaa.
La linealidad significa que podemos usar el principio de superposición, que a su vez quiere decir que tiene sentido que corrientes de múltiples lazos circulen por un mismo elemento del circuito. Tener varias corrientes significa que podemos utilizar las corrientes de lazo como variables independientes. ¡Y eso implica que podemos utilizar el método de la corriente de lazo para resolver circuitos!


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

* Se concluye que al formar mallas y aplicando leyes al respecto de las mismas se puede econtrar corriente, resistencia, voltaje al aplicar un sistema de ecuaciones.
* Se concluy que de manera experimental la carriente en cada malla puede ser similar o aproximado a los valores calculados con los valores medidios gracias a teroemas aplicados como ley de nodos o ley de kirchof.


8. BIBLIOGRAFÍA

Emplear normas APA para el informe e IEEE para el artículo

9. ANEXOS

