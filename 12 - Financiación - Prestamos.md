
## Como pasar de una Tasa Equivalente a otra

Cuando pasamos una Tasa Nominal a una Tasa Equivalente lo hacemos dividiendo a la Tasa Nominal por el número de capitalizaciones.  

Esa misma consideración es errónea si queremos pasar de una Tasa Equivalente a otra Tasa Equivalente que difiera en el período de tiempo.

> Las tasas son exponenciales, por lo que si yo hiciera para pasar una tasa equivalente mensual a una anual y multiplico por 12 a las tasa equivalente mensual, estaria cometiendo un **error** porque estaria linealizando la tasa de interes, y no es lineal, es exponencial.

Entonces como pasamos de una tasa equivalente a otra? ...

Dado que hay capitalizaciones dentro del período total, debemos hacerlo de la siguiente manera:

![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUekkHX-pgaLX6X8fiwh_xr9lHg5Iika6BJjQSWYakL7WX9xikc9lcQkWfD55AnYcTHheCfsp--49SijcRH-5jJ058wd__Fc7_j_VkUZjixSt6tC38_K29pJ3C1jmMMtgNy6bqfuQdbCk5X7S8wyRXWJQarELyKB=s2048?key=o4niJdCN_swDk8Y9_b_3ig)

Siendo “TEX” la Tasa Equivalente en un período determinado e “Y” la cantidad de veces que ese período entra en un año.

Entonces como seria para "tasa efectiva semestral" ? 

$$(1+TEA)^1 = (1+TEM)^{12} = (1+TES)^2$$

Como seria con la "tasa efectiva diaria"?

$$(1+TEA)^1 = (1+TEM)^{12} = (1+TED)^{365}$$

La tasa que convenga trabajar depende del ámbito de trabajo.
proyectos -> tasas anuales
comparación de tarjetas de créditos -> tasas mensuales

## Flujo de Efectivo Multiple


Generalmente necesitamos conocer el valor presente o futuro de un flujo de dinero que posee diferentes valores como también diferentes signos.  

La forma de resolver esto es simple pero tediosa: se llevan todos los flujos de dinero a la fecha buscada y se suman algebraicamente.

> Flujo de dinero: diferentes ingresos y egresos de efectivo que tenemos a lo largo del tiempo.

> "Llevar a misma fecha": pongo un periodo base y calculo respecto a las otras fechas "descontandolo". 

-> se refiere a **ajustar el valor de los flujos de dinero para que todos estén en el mismo punto del tiempo**, utilizando una tasa de interés o descuento. Esto es necesario porque el valor del dinero cambia con el tiempo debido a factores como la inflación o la oportunidad de inversión.

## Anualidades

Cuando un flujo múltiple de dinero cumple con las siguientes condiciones:

- Todas las cuotas son iguales.
- Todas las cuotas están separadas a la misma distancia de tiempo.
- El signo de todas las cuotas son iguales.
- Todas las cuotas tienen las mismas tasas.

Podemos calcular el valor presente del dinero de la siguiente manera:

![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUf6qQK-3v7tF3zKY77yLOy65-Gulk906G_tBoBJ1PTPEIh2lrsg01x_ovtrUcLM0OAfUcxMTVfZbgxJPLzgsS6yUghifAK3U2gfqUHg6Vcx9yD_H9-SpK2__2C0tHKvo05Ow_3zYWeHshnxC5yTGcwnYL7LnokF=s2048?key=o4niJdCN_swDk8Y9_b_3ig)

Siendo C la cuota mensual a pagar y a f se lo denomina “Factor”. Es importante destacar que el Factor siempre es menor a la cantidad de períodos (n).


## Perpetuidades

Cuando una anualidad es muy grande (n tiende a infinito), hablamos de una perpetuidad que se calcula de la siguiente manera.

![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUcJJCBPbu_Hr8gLUP1qAYhbpMTJ4RdJn1w3QVriQfzBBm2Rz1N7p-FgvM7XMbjKqDdql0gTxvV-aaR8ouJXtJZO3rT-uFBlJT_kF_UB_7gN6P1nml6JBDW4KA5pgC8QIDPLrcHjHrzVcKm9LoduKvVG0mWMV7A=s2048?key=o4niJdCN_swDk8Y9_b_3ig)

> Ejemplo: Los padres le pagan al hijo $1000 por anio al hijo hasta que se mueran. Pero cuanto representa $1000 por anio?  Es una *anualidad* porque cumple las 4 condiciones mencionadas, pero esta el detalle que n es muy grande, entonces n tiende a infinito y queda esa cuenta para el *VP*. 

> Entonces el valor presente de una anualidad es la cuota dividido la tasa de interés a la que descuento hoy. 

Si en el ejemplo la tasas de interés es del 5%, me queda VP = 1000/0.05 = $20000 sin tomar en cuenta la inflación.

La tasa de interes es la tasa de descuento, las tasas a las cual yo evaluo un proyecto. 
Es la tasa de referencia del mercado o del lugar que estoy trabajando.

> Estas cuentas no tienen en cuenta la inflación.

Side comments:
"Los bonos aumentan su valor cuando baja la tasa de interés"
"Y disminuyen su valor cuando aumenta la tasa de interés"
Ejemplo: Los bonos argentinos (ya emitidos) aumentaron su precio cuando EEUU bajo su tasa de interés.
-> Se compro a una tasa mayor, las tasas bajaron y ahora se tiene un bono que vale mas.
Los nuevo bonos pagan menos.

Un compra un bono para cobrar interés y para revenderlo si vale mas.

## Devolución de Préstamos

Un Préstamo es una operación financiera en la cual un ente presta una cantidad de dinero determinada a otro ente y éste se compromete a devolverlo mediante un documento legal que fija las cuotas, intereses, el tiempo en que debe devolverse y las penalidades en caso de incumplimiento.\

> Uno cuando pide un préstamo ya sabe todas las condiciones, todo se sabe de antemano.

>  El problema de una deuda no esta cuando se paga, sino cuando no se paga.

Los Préstamos (P) se componen de cuotas (C) y estas tienen 2 partes: la Amortización (A) que representa el capital prestado y el Interés (I) que representa el costo de ese dinero prestado.

Amortizacion -> devolucion de capital propiamente dicha.
Interes -> costo de dinero, lo que me cobra la entidad financiera.

A continuación veremos diferentes tipos de Préstamos.


## Sistema Francés 

Al Sistema Francés se lo conoce como **Préstamo de Cuota constante** e intereses sobre saldos. Cada período, el valor de la Cuota es el mismo pero varía la proporción de Amortización e Interés: en las primeras cuotas, la proporción de Interés sobre la Cuota es mayor y va disminuyendo período a período.

Los Intereses que pago período a período se calculan en base a la Amortización que me falta pagar.

El Sistema Francés es el sistema de Préstamos más frecuente.

Es importante destacar que, en caso de no poder seguir pagando un Préstamo y tener que refinanciar, voy a haber pagado poca Amortización que es lo que realmente cancela el Préstamo.

![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUfDxSxsifS_mesw-de1nJZrJBFgNKVrUnYEhAJdMlI_t_wPoqKLj5D-8VC_pF85owzGHMofaexiNqEXzI9ksaHGnN7JjfITpjMLn13PDXHPEReryb6ZmRi0G2daf97O9TzlfQA7pBpLDgGqO4yJaIMsSapktdI1=s2048?key=o4niJdCN_swDk8Y9_b_3ig)

El préstamo es igual a la sumatoria de las amortizaciones. 
Porque si hiciera la sumatoria de las cuotas me daría el préstamo mas el interés.
Y si hago la sumatoria de cuotas y le resto todo el prestamo la diferencia es el total de los intereses. 

> Los intereses se calculan sobre saldos -> El interes NO es sobre el total del prestamo, el interes va cambiando mes a mes porque se calcula sobre lo que debo.



## Sistema Alemán

Al Sistema Alemán se lo conoce como Préstamo de Amortización constante, Cuota decreciente e intereses sobre saldos. Cada período, el valor de la Cuota disminuye pero la Amortización que se paga es siempre la misma.

Los Intereses que pago período a período se calculan en base a la Amortización que me falta pagar.

El Sistema Alemán suele utilizarse para Préstamos entre Empresas.

A diferencia del Sistema Francés, en caso de no poder seguir pagando un Préstamo y tener que refinanciar, voy a haber pagado más Amortización para un mismo período dado.

![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUdWHsqt14iNAzkGzW_nesXgY_6VvIA-Rg7FBY4R6DC5R3BdLsjq1Mii8zAoT4X_woXDR0bFE65Kn2zGfMjf8sj3_4Hxzu0cmO6jeG_7wLwA2_dDprHqL8r3Qd37knXKFwNAaxDqtPbF7lKvW7dJXEiVX5pd9UY=s2048?key=o4niJdCN_swDk8Y9_b_3ig)


> La amortizacion es la misma para todos pero las cuotas son decrecientes porque va disminuyendo los intereses que se va pagando.

> En estos sitemas, tanto para el frances, el aleman y el bullet para un mismo monto con la misma tasa de interes y el mismo periodo de tiempo el valor presente, el prestamo es igual. Lo que cambia es la forma de devolver dinero.


## Sistema Bullet

Al Sistema Bullet se lo conoce como Préstamo de Cuota constante e intereses sobre saldos. En cada período se paga la Cuota que solo se compone del interés correspondiente y, en el último período, se paga todo el préstamo   

Los Intereses que pago período a período se calculan en base a la Amortización que me falta pagar; en este caso, todo el Préstamo.

El Sistema Bullet suele utilizarse en grandes negocios en los que el dinero se cobra todo junto en un mismo período.

En caso de incumpliento en este tipo de préstamo, la refinanciación es mucho más costosa que en los anteriores ejemplos porque nunca pago Amortización sino hasta la última cuota.

![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUfzG1RMsPnSAGZmp8JqH1fecK9_uNyxQXIiFW8Nxa4POd3y_sqSbJCF4ysR8vLD9rOo1VVfPBJgfbTFV8Tyg3X6I90LENQZxvbJ12jAEE1JoMjeXxjEwnHHq4GzEH3ZlMa43LLGRmrosWWWme8B634xudqLGrU=s2048?key=o4niJdCN_swDk8Y9_b_3ig)


> Se pide un prestamo de tipo Bullet cuando se esta seguro que el ingreso de dinero para pagar ese prestamo va a estar y va a estar mucho tiempo antes. 


## Sistema Directo

El Sistema Directo se denomina así porque los intereses se calculan directamente sobre la Deuda original a diferencia de los ejemplos anteriores en que los intereses se calculan sobre saldos. Hablamos de un sistema de Amortización constante e intereses constantes; por lo tanto, la Cuota es constante.

Este Sistema es engañoso porque permite publicar una tasa de interés más baja con iguales, peores o mejores resultados para el tomador del Préstamo. Es el Préstamo que ofrecen las entidades conocidas como “Efectivo Rápido”.


> Lo que vimos hasta ahora, es que uno paga intereses sobre saldos -> mientras mas pago menos intereses me cobran a la cuota siguiente. 
> Este metodo en cambio, me cobra intereses sobre el total del prestamo sin importar cuando haya pagado. 

En caso de incumpliento en este tipo de préstamo, la refinanciación es la más costosa de todas debido a que siempre pago intereses sobre el total de la Deuda.

![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUduhmlfmqEmuzgfteuxZlsUIuJkaUsuckOcMI9qwK7Sxj6dQ9LRKHMD4Hy4LmgDkKqr1XYLQYNHgwyBhY8fZiossNJy6kPrEUHjiRfG0lrVtA3Q88ISThL8qrXZVOsTrMEHiP4I3qQHIoWz-ZZCUAxyaC8l3mjq=s2048?key=o4niJdCN_swDk8Y9_b_3ig)

> Un 10% de tasa de interes en sistema directo es mayor que un 14% de tasa de interes en sistema de intereses sobre saldos. Porque ese 14% al ser sobre saldos cuando voy descontando si yo hiciera una tasa equivalente me da un numero menor al 10%.
> En el directo los 10 son 10.

> No tiene ninguna ventaja sobre los otros sistemas.

## Refinanciación de Préstamos

Si en algún momento se interrumpen las cuotas por imposibilidad de cumplimento, se deberá calcular cuál es la deuda en esa fecha trayendo, a ese instante de tiempo, todo lo que se habría pactado pagar, desde el instante del default, hasta la fecha final pactada.   

Esta suma se tratará como si fuese un nuevo préstamo, eventualmente con un método distinto de devolución de préstamos, con otra tasa de interés y otros plazos.


## Tasas de Interés e Inflación

Ante la presencia de inflación en la economía, se debe revisar el cálculo de las tasas de interés. La Tasa Efectiva es “Nominal respecto de la inflación”; por lo tanto, debemos calcular el efecto de la inflación en las tasas para obtener la “Tasa Real”.

Es importante destacar que es erróneo calcular la Tasa Real como la resta entre la Tasa Efectiva y la Tasa de Inflación (eso es solamente válido para análisis macroeconómicos donde la inflación ronda el 1%-2% anual).

> La tasa efectiva le falta el dato de la inflacion para ser completa. 
> Cuando metemos el calculo de inflacion hablamos de tasas reales.


![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUczjP8BQUkMQdQno0KPPMifMWlhkNw01M-QaHTGhptmyTBa9qaDOILH0n7EQFtVrB6FLhDM_gwiSitxcGb2qqTu-rdznj_bBGFciec2oZgFZ5KIE4ptQn75SR0qddiRdxPwlByNwN4jp19ThwWGLaR3tu51G-s=s2048?key=o4niJdCN_swDk8Y9_b_3ig)


## Tasas de Interés y Tipo de Cambio

Es importante destacar el papel que juega el tipo de cambio en las inversiones. Puede darse el caso de que hacemos una inversión en moneda local, atraídos por altos rendimientos y, durante ese período, el tipo de cambio aumente en forma considerable.

Como consecuencia de esto, podemos encontrarnos con que, al final de nuestro período de inversión, tengamos una ganancia en moneda local pero cuando dividimos ese monto por el tipo de cambio de ese momento, nos encontremos con menos dinero que al momento de hacer la inversión.







 

