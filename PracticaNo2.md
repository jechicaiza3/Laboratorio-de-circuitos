# Laboratorio-de-circuitos
|Carrera:Electrónica y automatización|Nivel:Segundo|Paralelo: A|
|---|---|---|
|Nombres:|Jefferson Chicaiza| Erick Izurieta|
|Tema:|Análisis de mallas| |
|Fecha de ralización:| 10/01/21|Fecha de entrega: 12/01/21|
|Ingeniero:| Darwin|Alulema |

1.-**OBJETIVOS**

General 

-Comprender el método de análisis de malla, y poder establecer una relación entre el uso de la Ley de Ohm y las Leyes de Kirchoff. Además de los conceptos básicos del análisis de circuitos.

Especificos

-Entender la importancia de tener claros los conceptos del análisis de circuitos, para   poder   llevarlos   a   la experimentación práctica.

-Identificar la forma correcta de medición de corriente y voltaje con el multímetro para circuitos resistivos, y más específicamente de los circuitos analizados por mallas.

-Comparar los cálculos teóricos con los prácticos de medición de tensión, intensidad de
corriente eléctrica y resistencias, y analizar el posible margen de error.

2.-**MARCO TEORICO**

El método de la corriente de malla es otro método bien organizado para resolver circuitos (el otro es el del voltaje en los nodos). Al igual que en cualquier análisis de circuito, tenemos que resolver un sistema de 2E2E2, E ecuaciones independientes, donde EEE es el número de elementos del circuito. El método de la corriente de malla facilita el análisis, y produce un número relativamente pequeño de ecuaciones a resolver.

El método de la corriente de malla se basa en la ley de voltaje de Kirchhoff (LVK).

El método de la corriente de lazo es una pequeña variación del método de la corriente de malla.

Lazos y mallas

El método de la corriente de malla utiliza dos términos especiales: lazo y malla.

![ley de kirchoff](https://user-images.githubusercontent.com/75336529/104218947-776df380-540b-11eb-99e5-7e8b42d7c406.png)

Un lazo es cualquier trayectoria cerrada alrededor de un circuito. Para formar un lazo, debes comenzar en la terminal de algún componente y trazar un camino a través de elementos conectados hasta llegar nuevamente al punto de partida.

3.-**DIAGRAMA**

![diagrama2](https://user-images.githubusercontent.com/75336529/104114304-eeeb3800-52d0-11eb-85ee-852eb00cabb1.png)

Diagrama 3.1: Circuito para el analisis de mallas.

4.-**MATERIAL Y EQUIPO REQUERIDO**
|Cantidad|Material o equipo|
|---|---|
|2|Fuentes de voltaje de C.D.|
|1|Multímetro digital|
|1|Resistor de 820 Ohm|
|1|Resistor de 390 Ohm|
|1|Resistor de 1 kOhm|
|1|Resistor de 1.2 KOhm|
|1|Resistor de 2.2 KOhm|
|1|Protoboard|

5.-**EXPLICACIÓN**

**5.1.-** Implemente el circuito en un simulador sea tinkercad o multisim.

**5.2.-** Mida el valor de cada malla y anotelo en la tabla que se muestra a continuación.

**5.3.-** Obteniendo los valores compare con los resultados que obtuvo de forma analitica.

6.-**TABULACIÓN DE DATOS**
|MALLA|RESULTADOS ANALÍTICOS|RESULTADOS MULTISIM|RESULTADOS TINKERCAD |
|---|---|---|---|
|1| 11.45mA| 11.46mA|11.5mA|
|2| 2.85mA| 2.84mA|2.85mA|
|3| 488uA| 488uA |488uA|

7.-**DESCRIPCIÓN DE PREREQUISITOS Y CONFIGURACIÓN**

Se requiere el análisis analítico del circuito mostrado en el diagrama 3.1.

Se requiere tener los materiales y equipos mencionados o a su vez tener una cuenta en el simulador Tinkercat.

8.-**APORTACIONES**

-Al momento de realizar una medición en los circuitos, se recomienda usar la escala mayor en nuestro multímetro (en caso de no ser autoajustable), debido a que la escala que usamos puede ser menor al valor entregado por el elemento y podría dañar los instrumentos de medida. Y luego ajustar a una escala donde se pueda apreciar la medida con mayor claridad. 

- Se recomienda primero construir el circuito y comprobar la cantidad en todos los nodos que hayan antes de conectar a una fuente ya sea de voltaje o corriente.

-Al momento de realizar las mediciones, se recomienda no topar con los dedos o ninguna parte del cuerpo las puntas del multímetro, debido a que el cuerpo humano proporciona una resistencia propia, por lo que puede distorsionar el resultado real de la medición realizada.

9.-**CÁLCULOS**

![CALCULOS](https://user-images.githubusercontent.com/75336529/104233327-b148f500-541f-11eb-916b-003e63066369.png)

Para realizar los calculos de las mallas se utiliza  las leyes de kirchhoff  en la cual al analizar  las mallas se generan tres ecuaciones con tres incognitas las cuales se las resuelve y nos da como resultado  la corriente que sircula por cada malla.

10.-**CONCLUSIONES**

*Habiendo simulado y montado el circuito, se obtienen las corrientes con valores teóricos ideales, y los prácticos, dando a conocer el funcionamiento del método de análisis de malla, que solo es aplicable a circuitos planos, es decir, donde no exista cruce de ramas.

*Aplicando la teoría de análisis de mallas, nos damos cuenta de que esta bien fundamentada y puede ser aplicable de modo general a cada circuito plano que se pueda presentar.

*Observamos que no hay un porcentaje de error significativo entre en fundamento ideal o teórico, respecto a un experimental, puesto que los elementos usados durante la práctica, no iterfieren bastante en la forma de valores.

*Y   de   lo   anterior, se   concluye   que   el método   de   Análisis   de   Mallas   es   un
método práctico y muy útil para el análisis de   circuitos, y   que   no   requiere   tanta
complejidad, aunque   existan   variaciones en su forma de aplicarlo.

11.-**BIBLIOGRAFIA**

https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-mesh-current-method

12.-**ANEXOS**

![circuitof](https://user-images.githubusercontent.com/75336529/104231939-a2614300-541d-11eb-8435-82cd86939e91.jpeg)

Imagen 1: Diagrama implementando en la protoboard.

![multisim](https://user-images.githubusercontent.com/75336529/104221686-3c6dbf00-540f-11eb-8a01-6f94cedbe29e.png)

Imagen 2: Simulador Multisim.

![corrientes mul](https://user-images.githubusercontent.com/75336529/104225152-02eb8280-5414-11eb-8bd5-26a4bdd60130.png)

Imagen  3: Toma de datos de corrientes medidas en el simulardor Multisim.

![simulador Tinkercad ](https://user-images.githubusercontent.com/75336529/104230471-a1c7ad00-541b-11eb-8c2f-a125426e9096.png)

Imagen 4: Simulador Tinkercad.

![amperaje tinkercad](https://user-images.githubusercontent.com/75336529/104230485-a55b3400-541b-11eb-8f92-870007bc8817.png)

Imagen 5: Toma de datos de corrientes medidas en el simulador Tinkercad.
