# Laboratorio-N6
## Integrantes: Gaona Carlos, Masaquiza Alex, Morillo Ariel
## NRC: 5407

**1. OBJETIVOS**

_Objetivo General_

-Determinar experimental y analiticamente las condiciones necesarias para hallar la maxima transferencia de Potencia.

_Objetivos Específicos_

-Comprender y aplicar los fundamentos basicos del teorema.

-Calcular la potencia  de cada resistencia equivalente  en el circuito.

-Analizar  el  efecto  de  la  variación  de  la  carga  en  la  potencia  entregada  por  un circuito.

**2. MARCO TEÓRICO**

![1l6](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/1l6.PNG)

![2l6](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/2l6.PNG)

**3. EXPLICACIÓN DEL PROCEDIMIENTO**

Tenemos el siguiente diagrama eléctrico con el cual realizaremos nuestra práctica en el simulador tinkercad.

![Paso 0](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Diagrama%20lab6.png)

1.  Seleccionamos los materiales que vamos a usar para nuestra practica, en este  caso necesitaremos.

![Materiales](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Materialeslab6.png)

![Paso 1](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Paso%201.png)

2.  Colocamos las resistencias en el protoboard en sus respectivas posiciones, de acuerdo al diagrama eléctrico planteado para la práctica. Por lo tanto tenemos lo siguiente:

![Paso 2](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Paso%202.png)

3.  Interconectamos las resistencias con su respectivo cableado (rojo +, negro -) siguiendo el diagrama eléctrico, por lo tanto tenemos:

![Paso 3](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Paso%203.png)

4.  Conectamos la fuente de voltaje al protoboard y asignamos un suministro de energía de 15V.  

![Paso 4](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Paso%204.png)

5.  Iniciamos la simulación de nuestro circuito, medimos el voltaje y la corriente en el resistor RL.

![Paso 5.1](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Paso%205.1.png)

![Paso 5.2](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Paso%205.2.png)

![Paso 5.3](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Paso%205.3.png)

![Paso 5.4](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Paso%205.4.png)

![Paso 5.5](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Paso%205.5.png)

![Paso 5.6](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Paso%205.6.png)

![Paso 5.7](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Paso%205.7.png)

![Paso 5.8](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Paso%205.8.png)

![Paso 5.9](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Paso%205.9.png)

![Paso 5.10](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Paso%205.10.png)

6.  Usaremos en simulador Dcaclab, para medir la potencia en el resistor RL 220 Ω, repetir el proceso con todas las resistencias RL.

![Paso 6](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/Paso%206.png)

**4. RESPUESTAS A INTERROGANTES Y CALCULO DE ERROR**  

4.5.2 Mida el voltaje y la corriente para cada valor de RL que se indica en la tabla 6.1. Anote los resultados medidos.       
4.5.3 Calcule las potencias consumidas por RL, para cada valor dado y anote los resultados en la tabla 6.1.        
![calculos](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/calculoslab6.png)        
![calculos_1](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/calculoslab6_1.png)     

Tabla 6.1. Parámetros Eléctricos del circuito de la figura 6.1.       
![tabla](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/tabla.png)    

4.5.4. ¿Se cumple el Teorema de la Máxima Transferencia de Potencia? Argumente su respuesta. 

No se cumple el Teorema de Máxima Transferencia de Potencia ya que el teorema indica que RL recibirá la máxima potencia solamente cuando el valor de la resistencia interna de la fuente sea igual al valor de la resistencia equivalente RL, es decir RS=RL, como en este caso no tenemos una resistencia RL de 1200 Ohms no se puede cumplir el teorema.     

4.5.5. ¿Cuál fue la potencia máxima en RL?     
0.046 Watts      

4.5.6. ¿Para qué valor de RL se obtiene la MTP?     
1000 Ohms

4.6.7. Calcule el error.   
![error](https://github.com/AlexMP98/Laboratorio-N6/blob/main/Imagenes/error.png)    


**5. VIDEO**

Link del video:  https://youtu.be/ovm7CxOl-Yk

**6. CONCLUSIONES**

-La reduccion de un circuito complejo a una fuente y resistencia de Thevenin nos ayuda para poder determinar más rápido la transferencia de potencia hacia un resistor.      

-Dada una cierta resistencia de carga, la resistencia de fuente que maximiza la transferencia de potencia es siempre cero, independientemente del valor de la resistencia de carga.

**7. BIBLIOGRAFÍA**

CIRCUITOS ELÉCTRICOS, J.W. Nilsson. Ed. Addison-Wesley Iberoamericana, 1995.
Fundamentos de Circuitos Eléctricos. Charles K. Alexander y Matthew N. O. Sadiku. McGraw-Hill Companies, Inc.

