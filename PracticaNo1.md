# Laboratorio-de-circuitos

|Carrera: Electrónica y automatización|Nivel: Segundo| Paralelo A|
|---|----|---|
|Nombres:| Erick Izurieta|
|Tema:| Leyes de Kirchhoff||
|Fecha de realización: |17/12/2020|Fecha de entrega: 22/12/2020|
||Ingeniero: Darwin Alulema||


1.-OBJETIVOS	

General		

Explicar y demostrar experimentalemnte la Ley de Kirchhoff de Voltajes y la Ley de Kirchhoff de corrientes.
		

Especificos	

Comprender el uso correcto de los distintos instrumentos y elementos electrónicos.

Aplicar el uso correcto del mult´ımetro para medir voltaje, corriente y la cantidad de resistencia de un resistor.

Comparar las leyes de Kirchhoff entre lo teorico y lo veridico.

2.-MARCO TEORICO

Las leyes de Kirchhoff fueron formuladas por Gustav Kirchhoff en 1845, mientras aun era estudiante. Son muy utilizadas en ingeniería eléctrica para obtener los valores de la 
corriente y el potencial en cada punto de un circuito eléctrico. Surgen de la aplicación de la ley de conservación de la energía.

![leyes](https://user-images.githubusercontent.com/75336529/102168900-14fef300-3e5f-11eb-88ce-9c6e21603743.PNG)

La razón por la cual se cumple la primera ley se entiende perfectamente en forma intuitiva si uno considera que la corriente eléctrica es debida a la circulación de electrones de un punto a otro del circuito. Piense en una modificación de nuestro circuito en donde los resistores tienen un valor mucho mas grande que el indicado,de modo que circule una  corriente eléctrica muy pequeña, constituida por tan solo 10 electrones que salen del terminal positivo de la batería. Los electrones están guiados por el conductor de cobre  que los lleva hacia el nodo 1. Llegados a ese punto los electrones se dan cuenta que la resistencia eléctrica hacia ambos resistores es la misma y entonces se dividen circulando  5 por un resistor y otros 5 por el otro. Esto es totalmente lógico porque el nodo no puede generar electrones ni retirarlos del circuito solo puede distribuirlos y lo hace en  función de la resistencia de cada derivación. En nuestro caso las resistencias son iguales y entonces envía la misma cantidad de electrones para cada lado. Si las resistencias fueran diferentes, podrían circular tal ves 1 electrón hacia una y nueve hacia la otra de acuerdo a la aplicación de la ley de Ohm. 

La ley de Ohm establece la relación que guardan la tensión y la corriente que circulan por una resistencia. Su forma más célebre es:

                                                                V=I.R
                                                                
Tambien se lo relaciona con un trinagulo:
 
![triangulo](https://user-images.githubusercontent.com/75336529/102174229-f0107d00-3e6a-11eb-82cc-bca25dbda616.jpg) 

Donde: I: Es la corriente medida en ampers(A)

V: Es la tención que circula por el circuito medidda en Volts(V)

R: Es la resistencia eléctrica que se opone al paso de corriente medida en Ohms

Para armar un circuito necesitamos de algunos elementos básico como son:

![Componentes](https://user-images.githubusercontent.com/75336529/102168912-18927a00-3e5f-11eb-9dbb-971b2609bba6.PNG)

3.-DIAGRAMA

![diagrama](https://user-images.githubusercontent.com/75336529/102167982-71611300-3e5d-11eb-913b-5dbd21f5e7a6.PNG)

Diagrama 1: Circuito Resistivo mixto

3.-MATERIAL Y EQUIPO REQUERIDO

![equipos](https://user-images.githubusercontent.com/75336529/102169795-fb5eab00-3e60-11eb-9628-9f3b1ce8e325.png)

5.- EXPLICACIÓN

5.1.-Realice el circuito visto en el diagrama 1 en el simulador de tinkercad.

5.2.-Con los multímetros proceda a medor el voltaje en cada uno de los resistores y anote los resultadas en la tabla correspondiente.

5.3.-Con el mismo multímetro colóquelo para medir corriente, proceda a medir la corriente en cada uno de los resistores y coloque los resultados en la tabla correspondiente.

5.4.-Con los valores obtenidos proceda a verificar que se cumple la ley de Kirchhoff.

5.5.-Con los valores obtenidos analíticamente y los valores medidos proceda a compararlos.

6.-TABULACIÓN DE DATOS

Tabla 1: Resultados obtenidos de voltaje y corriente en cada elemento del circuito.

![valoresmedidos](https://user-images.githubusercontent.com/75336529/102169811-ff8ac880-3e60-11eb-9a0e-cf95a346e802.png)

Tabla 2: Verificación de la L.V.K.

![tablav](https://user-images.githubusercontent.com/75336529/102169808-fe599b80-3e60-11eb-86e2-c9d962a6b1bb.png)

Tabla 3: Verificación de la L.C.K.

![tablaa](https://user-images.githubusercontent.com/75336529/102169806-fdc10500-3e60-11eb-8c3d-fe5b60aff8f5.png)

7.- DESCRIPCIÓN DE PREREQUSITOS Y CONFIGURACIÓN

Se requiere conocimiento previo de las leyes de Kirchhoff.

Se requiere el análisis analítico del circuito mostrado en el diagrama 1.

Se requiere tener los materiales y equipos mencionados o a su vez tener una cuenta en el simulador Tinkercat.

8.-APORTACIONES

Los valores teoricos comparados con los valores prácticos tienen un porcentaje de erro muy pequeños por lo que podriamos decir que al hacer el cálculo teórico nos da valores casi reales tomando en cuenta que son condiciones ideales en las que se realiza el cálculo teórico.

9.-CÁLCULOS

Corriente en la malla:

![calculoi](https://user-images.githubusercontent.com/75336529/102169786-f7cb2400-3e60-11eb-877a-a9913a2e7366.png)

En éste cálculo se aplica la ley de voltajes de Kirchhoff entre las dos mallas que se generan y se resuelve un sistema de ecuaciones con dos incógnitas.

Voltaje

![calculov](https://user-images.githubusercontent.com/75336529/102169793-f994e780-3e60-11eb-8165-e4117d4db251.png)

En éste cálculo se aplica la le de Ohm para saber el voltaje que cae en cada elemento del circuito.

Corriente en cada elemento

![Corriente un elemento](https://user-images.githubusercontent.com/75336529/102169794-fa2d7e00-3e60-11eb-9dcb-89321431240b.png)

En éste cálculo se depeja la intensidad de corriente de la ley de Ohm y se realiza la operación.

Porcentaje de error en el voltaje 

![errorv](https://user-images.githubusercontent.com/75336529/102169803-fd286e80-3e60-11eb-8cde-85a138b2dce8.png)

Porcentaje de error en la corriente

![errora](https://user-images.githubusercontent.com/75336529/102169797-fbf74180-3e60-11eb-86f8-864ae3127b76.png)

10.-CONCLUSIONES

Después de haber realizado la practica en el simulador hemos podido analizar, los diferentes instrumentos para crear circuitos, como son las resistencias, Protoboard, fuente de energía; notamos la importancia de cada uno, su utilidad, cómo utilizar el multímetro, distinguir la diferencia entre circuito en serie a circuito en paralelo, y la importancia de cada uno, puesto que en el circuito en serie se suma la capacidad de cada resistencia, haciendo una de mayor capacidad; en cambio en paralelo, las resistencias tienen un valor proporcional entre si. 

El Protoboard es una herramienta útil para el planteamiento de circuitos eléctricos ya que en el casi no existe interferencia de corrientes externas como cuandotomamos el circuito con las manos.

Se pudo observar la diferencia entre los valores reales o los que deberías ser y los valores que se midieron, hubo una pequeña diferencia, pero son casi los mismo, esto es que al medirlos hay un margen de error muy pequeño. 

En la práctica se conocieron algunos instrumentos de medición como el multímetro, Protoboard y se aprendió a utilizarlos de manera adecuada. Se aprendiócomo medir la capacidad de una resistencia con la ayuda del Protoboard, y las formas distintas de armar circuitos. 

11.-BIBLIOGRAFIA

LeyesdeKirchhoff:(2020; 11junio):electronicacompleta:https : ==electronicacompleta :com=leyes − de − kirchhoff=

J:L:F:(2018):LeydeOhm:F ISICALAB:https : ==www:fisicalab:com=apartado=ley− de − ohm

F errer; V:(2016):Queesunprotoboardobreadboard:V icenteF errer:https : ==vicentferrer:com=protoboard − breadboard=

VIDEO: 

https://www.youtube.com/watch?v=a_x5jgSeAVQ&feature=youtu.be

12.-ANEXOS

![circuito1](https://user-images.githubusercontent.com/75336529/102167975-6d34f580-3e5d-11eb-9b02-1c570aa1fdba.jpg)

Imagen 1: Circuito hecho en una protoboard.

![panel](https://user-images.githubusercontent.com/75336529/102167989-745c0380-3e5d-11eb-9eda-8573dacb67b6.png)

Imagen 2: Panel principal de Tinkercat.

![circuitoi](https://user-images.githubusercontent.com/75336529/102167977-6f974f80-3e5d-11eb-93c2-cef204cb5b4a.png)

Imagen 3: Circuito armado en Tinkercat.

![voltaje](https://user-images.githubusercontent.com/75336529/102167996-76be5d80-3e5d-11eb-97ff-c2fd0e9f753e.png)

Imagen 4: Toma de datos del voltaje medido en dos resistores.

![amperaje](https://user-images.githubusercontent.com/75336529/102167887-48408280-3e5d-11eb-9f3d-3ad0ebb9136f.png)

Imagen 5: Toma de datos de Intensidad de la corriente me dida en un resistor.
