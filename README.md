# PR-CTICA-No.-1_LEYES-DE-KIRCHHOFF
**1.1. OBJETIVO DE LA PRÁCTICA**

- Explicar y demostrar experimentalmente la Ley de Kirchhoff de Voltajes y la Ley de Kirchhoff de Corrientes.

**1.2. MARCO TEORICO:**

•	*Leyes de Kirchhoff:* Es un de los métodos ampliamente utilizados en el análisis de circuitos eléctricos de voltaje y corriente, puesto que con ellas se puede determinar el valor de voltaje o corriente en cualquier elemento que forme parte del circuito. Las Leyes de Kirchhoff se enuncian a continuación:

•	*Ley de Kirchhoff de Corrientes:* La suma de las corrientes que entran a un nodo es igual a la suma de las corrientes que salen del mismo.

•	*Ley de Kirchhoff de Voltajes:* La suma de las caídas de voltaje en una trayectoria cerrada es igual a la suma de las elevaciones de voltaje en la misma.

•	*Voltaje:* Fuerza que ordena el movimiento del flujo de electrones. Es medida en (V) voltios en honor a Alessandro Volta.

•	*Corriente:* Es la velocidad de la carga respecto al tiempo, y su unidad de medida es en (A) amperios.

**MATERIAL O EQUIPO:**

•	*Fuente de Voltaje de C.D.:* Dispositivo que a partir de la tensión de red pueden proporcionar una señal de tensión continúa para alimentar al circuito.

![Fuente de voltaje CD](https://user-images.githubusercontent.com/116777118/201383154-7c2508a6-11ad-4d5d-8d1a-4ed1f87034ae.jpg)

•	*Multímetros Digitales:* Es una herramienta que es usada para medir valores eléctricos, principalmente tensión (voltios), corriente (amperios) y resistencia (ohmios).

![multimetro_1](https://user-images.githubusercontent.com/116777118/201382969-7fb13348-0cf4-4ec7-81d6-f15be2d07d6d.jpg)

•	*Resistores:* Componente electrónico diseñado para introducir una resistencia eléctrica determinada entre dos puntos de un circuito eléctrico.

![resistor-definicion](https://user-images.githubusercontent.com/116777118/201383057-d8402a5c-2f47-4a00-b7f9-de3d5b46dc2b.jpg)

a)	Resistor de 1 kΩ:

b)	2 Resistores de 2.2 kΩ

c)	Resistor de 1.8 kΩ

d)	Resistor de 3.9 kΩ

•	*Protoboard:* Es una placa de pruebas en los que se pueden insertar elementos electrónicos y cables con los que se arman circuitos sin la necesidad de soldar ninguno de los componentes.

![Protoboard-1660-puntos_2](https://user-images.githubusercontent.com/116777118/201383269-cf7137c9-42c7-4518-a4d0-e81ccca286d7.jpg)

**1.3. PROCEDIMIENTO**

1.	Armar el circuito que se muestra en la figura 1.1 en Thinkercad.

![Procedimiento_1](https://user-images.githubusercontent.com/116777118/201383371-bc596746-c2b4-42a3-be26-d0f5a1c4fa57.jpg)

Para facilitar el procedimiento de los cálculos y el entendimiento del circuito, lo analizamos por partes. 

![Para facilitar el procedimiento de los cálculos y el entendimiento del circuito, lo analizamos por partes  ](https://user-images.githubusercontent.com/116777118/201383444-9a1f828e-ef09-4561-851d-e26d2c80ce84.jpg)

Ahora tenemos solamente una resistencia total, la que nos permitirá encontrar los datos preliminares previos a los cálculos. 

*1.	Sumamos las resistencias que se encuentran en serie dentro del circuito en paralelo*

![1Sumamos las resistencias que se encuentran en serie dentro del circuito en paralelo](https://user-images.githubusercontent.com/116777118/201383531-7f291ad5-8f28-47e4-aac9-ffc4f6ae1bbf.jpg)

*2.	Ahora que tenemos R6, podemos sumar las resistencias del circuito en paralelo.*

![2Ahora que tenemos R6, podemos sumar las resistencias del circuito en paralelo  ](https://user-images.githubusercontent.com/116777118/201383690-113e57e9-77bf-4d6f-b5f7-3047535c0efb.jpg)

*3.	Por último, sumamos todas las resistencias en serie del circuito completo.*

![3Por último, sumamos todas las resistencias en serie del circuito completo](https://user-images.githubusercontent.com/116777118/201383732-1f9eefcc-5203-4a1d-baa3-1a48a61cdb92.jpg)

*4. Teniendo la resistencia total, podemos encontrar la intensidad de corriente total del circuito conociendo que la intensidad es igual al voltaje sobre resistencia.*

![4Teniendo la resistencia total](https://user-images.githubusercontent.com/116777118/201383767-86679df5-1176-4765-a91e-53b9d966fae7.jpg)

*5. Conociendo la intensidad de corriente del circuito, conocemos que, en circuitos en serie la intensidad es la misma para cada elemento, por lo tanto, podemos calcular el voltaje en dichos elementos.*

![5Conociendo la intensidad de corriente del circuito](https://user-images.githubusercontent.com/116777118/201383813-75a9a4e2-1b3b-4f20-9221-e923de1f8368.jpg)

*6. Para encontrar el voltaje en R5, conociendo la intensidad de corriente total.*

![6Para encontrar el voltaje en R5](https://user-images.githubusercontent.com/116777118/201383884-11b0c3e0-6d21-4809-9130-dd7366c3e475.jpg)

*7. Para encontrar el voltaje en R7, conociendo la intensidad de corriente total.*

![7Para encontrar el voltaje en R7](https://user-images.githubusercontent.com/116777118/201383906-7b9bc9cc-c3bf-40dd-b557-f0d5501a3d71.jpg)

*8.	Conociendo el voltaje en R7, como de esta se deriva el circuito en paralelo que sintetizamos, podemos determinar que el voltaje será el mismo para todos sus elementos, mientras que, la intensidad es diferente en cada uno, por lo tanto, vamos a encontrar dichas intensidades en R2, R3 y R4.*  

![8Conociendo el voltaje en R7](https://user-images.githubusercontent.com/116777118/201383933-a6eae9f1-435d-4b2c-a978-cb270559b2ce.jpg)

*9.	Como tenemos la intensidad de corriente en R3 - R4  y estas son en serie, podemos decir que tienen la misma intensidad de corriente, pero diferente voltaje, sin embargo, tienen el mismo valor de resistencia, por esta ocasión, será el mismo.*

![9Como tenemos la intensidad de corriente en R3 - R4  y estas son en serie](https://user-images.githubusercontent.com/116777118/201383973-b9fb5a84-2fd0-4f70-8d5c-94b40068e271.jpg)

Realizamos las mediciones de voltaje e intensidad de corriente de cada elemento del circuito. 

*Voltaje Total*

*Voltaje en R1*
 
*Voltaje en R2*
 
*Voltaje en R3*
 
*Voltaje en R4*
 
*Voltaje en R5*
 
*Intensidad total*
 
*Intensidad en R1*

*Intensidad en R2*
 
*Intensidad en R3*

*Intensidad en R4*
 
*Intensidad en R5*

Tabla de resultados con las respectivas mediciones de voltaje e intensidad de corriente de cada elemento.

![TABLA VARIABLE_VALOR CALCULADO_VALOR SIMULADO](https://user-images.githubusercontent.com/116777118/201384211-b359ade7-8b60-4b0d-9f7a-364500fe315e.jpg)

**Cálculos de la Ley de Voltaje de Kirchhoff**

Conocemos que:

![Cálculos de la Ley de Voltaje de Kirchhoff ](https://user-images.githubusercontent.com/116777118/201384439-581240a6-3873-409c-8b2d-f088f9323ed9.jpg)

Esta ley podemos analizar en circuitos en serie, ya que, el voltaje se reparte para cada elemento. El voltaje de inicial debe ser igual al voltaje de salida o también que la suma algebraica de todos los voltajes (tanto de fuente como de caídas) localizados en una trayectoria cerrada única es cero.

En el respectivo circuito podemos visualizar tres trayectorias respectivamente: 

![En el respectivo circuito podemos visualizar tres trayectorias respectivamente](https://user-images.githubusercontent.com/116777118/201384551-ab71b540-c01c-4074-aebd-ebd68b80b300.jpg)

**Tabla de resultados de la Ley de Voltaje de Kirchhoff respecto al circuito.**

![TABLA VOLTAJE_TRAYECTORIA 1_TRAYECTORIA 2_TRAYECTORIA 3](https://user-images.githubusercontent.com/116777118/201384687-68f0962f-69d4-4e39-abe6-ea3b728b7ae5.jpg)

**Cálculos de la Ley de las Corrientes de Kirchhoff**

Conocemos que:

![Cálculos de la Ley de las Corrientes de Kirchhoff ](https://user-images.githubusercontent.com/116777118/201384784-391a1b94-5ab7-4bb8-91d8-cdc151f26b0a.jpg)

Esta ley podemos analizar en circuitos en paralelo, ya que, el voltaje es constante, mientras que la intensidad de corriente se reparte para cada dirección. La intensidad de entrada debe ser a la intensidad de salida o también que la suma algebraica de todas las corrientes que entran y salen de un nodo es igual a cero.

En el respectivo circuito podemos visualizar los nodos respectivamente: 

![En el respectivo circuito podemos visualizar los nodos respectivamente](https://user-images.githubusercontent.com/116777118/201384885-184c5415-b895-4674-ae12-9633874039a8.jpg)

**Tabla de resultados de la Ley de las Corrientes de Kirchhoff respecto al circuito**

![Tabla de resultados de la Ley de las Corrientes de Kirchhoff respecto al circuito](https://user-images.githubusercontent.com/116777118/201384992-9bdc3f3b-1664-4d7c-9e24-6af39e3a36c7.jpg)

Podemos observar que las leyes de Kirchhoff se cumplen en nuestro circuito y que coincide exactamente con los cálculos realizados para demostrarlas tanto experimental como analíticamente. 

*Errores de Cálculo:**

![Errores de Cálculo](https://user-images.githubusercontent.com/116777118/201385062-eaf0b1f6-7cb9-4905-b836-65cb3f54523c.jpg)

**Todos los valores medidos y calculados poseen un error del 0%.**

**Ejemplo.**

![EJEMPLO DE ERROR](https://user-images.githubusercontent.com/116777118/201385137-916c11d3-fb12-4efc-b6ec-2a6bd79dfd63.jpg)

**1.4. VIDEO**

https://youtu.be/SSZin3_pG3s

**1.5. CONCLUSIONES**

•	Se consiguió demostrar las dos leyes de Kirchhoff tanto la de voltajes como la de corrientes en el respectivo circuito para la práctica. 

•	Se determinó que, en circuitos en serie, la intensidad de corriente es la misma para cada elemento, puesto que, sigue una solo dirección, mientras, el voltaje es distinto, además la suma algebraica de la fuente y las caídas de voltaje siempre es cero. 

•	Se determinó que, en circuitos en paralelo, el voltaje es el mismo para cada elemento mientras que la intensidad de corriente se reparte en las distintas direcciones, además la suma algebraica de la intensidad de entrada y salida en los respectivos nodos siempre es cero. 

•	La ley de ohm se aplica con constancia en este tipo análisis y es la raíz inicial para las aplicaciones de distintas leyes y fórmulas con respecto a circuitos eléctricos. 













