# Conclusiones de Ánalisis de Venta
## Tendencias observadas
Por lo general, la media de las distribuciones era mucho menor que la mediana, lo que nos informaba de la presencia de datos atípicos en todas las variables.

### Ventas
    En la variable ventas se observó una gran variabilidad en los datos, que nos daba información respecto al rango de nuestras ventas que oscilaba desde las 0,44€ hasta 2298194,76 €. se concluye que hay una concentración de ventas de valores bajos con cantidades de ventas de un gran valor atípico (por encima del tercer cuartil) que sesgan la media (229.91€) al alza, en contraposición con el bajo valor de la mediana (54,41€)
### Descuento
    Más de la mitad de nuestras ventas tiene una reducción en el precio de venta de 1€ sin embargo, la media de 32,27€ nos señala que hay un número de pedidos que tienen unos descuentos muy superiores y aumentan la media. 
### Beneficio
    La media de la distribución de beneficio es de 28,68€ frente a una meidana de 8,67€
El cálculo de los cuatiles para los beneficios positivos fue muy util para una compresión general de los beneficios que aportaba las ventas. En esta llínea el quartil primero quedaba en 5,25€ por lo que 1/3 de nuestras ventas aportaban un beneficio entre 0-5,31€- El segundo cuartil de 13,31€ nos informaba que la 2/3 de los beneficios de nuestros datos se comprendían entre 5 y 13€. El último cuartil nos informaba que la terecera parte de nuestros beneficios oscilaban valores entre 12-40,5€. El tratamiento de todos los beneficios superiores al último cuartil se trató como valor atípico. 
### Costo de producción
    De media, el costo de producción es de 168.96€ aunque la mediana con un valor mucho menor de 35.72€ nos informa de que de la mitad de nuestras transacciones tienen un costo de preoducción alrededor de los 35€, pero hay productos específicos que nos suponen un costo de producción mucho mayor que sesga la media al alza.
a pesar de la importancia que puede tener esta variable para el rendimiento general de la empresa, mi análisis se centro en fundamentar decisiones para tomar estrategias según el beneficio.
### Tiempo de envío
    En términos generales puede concluirse que el tiempo de envío no es una variable que afecte a las ventas, beneficios ni costos de producción, por lo que no se le ha prestado especial atención más que el análisis de ver de media cuánto tarda un envío en procesarse (4 días) teniendo algunas expecepciones donde el tiempo excede a la emedia y mediana siengo un máximo de 7 días. 
### Precio de venta
    La media del precio de venta está en 262€ frente a una mediana de 60€ lo que nos indica que hay productos con un precio de venta mucho más alto de lo normal. 


    En términos generales, puede decirse que en nuestros datos hay productos clave, que hacen aumentar la media de todas las trasacciones. Aunque a modo general nuestros beneficios, costos de producción y precio de venta oscilen en valores "bajos-medios"
tenemos productos que ofrecen una oportunidad para aumentar los beneficios de la empresa y mejorar el rendimiento. Sería muy interesante analizar qué productos y bajo qué condiciones (descuentos, precio de venta, estado) hacen que X transacciones aumenten tanto la media de la distribución de nuestras variables.

## Correlaciones más relevantes

- La correlación más relevante encontrada fue Una correlación de -0,9537 entre las ventas y el coste de producción, que indica una relación negativa fuerte entre ambas variables. Esto significa que cuando los costes de producción aumentan, las ventas tienden a disminuir, es decir, que se mueven en direcciones opuestas.
Aunque correlación no implica causalidad, gestionar los costes de producción podría ser clave para la empresa, ya que aparentemente afectan de manera importante la capacidad de ventas.
Por un lado, podría decirse que los aumentos en el coste de producción están afectando de manera significativa la capacidad de venta, de manera que cuando un producto cuesta mucho prodcuri el precio de venta aumenta igualmente y esto afecta a la demanda del producto. Otra posible interpretación es la inversa: en un escenario donde a la empresa le cuesta muy poco producir ciertos tipos de productos, puede alcanzar un mayor margen de beneficio y aumentar las ventas. 

Un estadístico que añade valor a la hora de formular las hipótesis en este sentido es la correlación entre el precio de venta (con el descuento aplicado) y el coste de producción. Este estadístico fue el segundo más relevante estadísitvamente con un -0,952. 
Esto implica que cuando el coste de producción es alto, es posible que la empresa tenga que reducir el precio de venta para mantener la competitividad y estimular las ventas.  Puede que la empresa esté implementando descuentos significativos en el precio de venta como respuesta a un aumento en los costes de producción, posiblemente para seguir siendo atractiva para los consumidores. Esto puede ser una estrategia para impulsar las ventas en un contexto donde los costes son altos.
Puede que la empresa esté implementando descuentos significativos en el precio de venta como respuesta a un aumento en los costes de producción, posiblemente para seguir siendo atractiva para los consumidores.
Esto puede ser una estrategia para impulsar las ventas en un contexto donde los costes son altos.
Esta hipótesis es la que más coherencia denota en el análisis de beneficio que se hizo posteriormente y se detallará a continuciación. En este análisis se observó que los descuentos superiores al 0,20 aplicados a productos y en condiciones concretas son aplicados y aunque aumentan el volumen de ventas, genera pérdidas a la empresa.
La empresa puede estar atrapada en un ciclo donde necesita ofrecer descuentos para atraer cliente y de esta manera pierde beneficios.

- La anterior hipótesis se refuerza al analizar correlación positiva moderada entre Sales y Total Discount (0.61), que  nos indica que la estrategia de descuento tienen efecto considerable en las ventas, ya que un descuento más alto suele estar asociado con mayores ventas. A mayor descuento, mayor volumen de ventas. 
Esta interpretación podría evaluarse para ver si el descuento es realmente lo que impulsa el volumen lo suficiente para justificar esa reducción en el precio. Si no, podría considerarse aplicar descuentos sólo a productos específicos de alto margen para manetener la rentabilidad. 

- Por otro lado, la correlación negativa baja entre rentabilidad y total discount es lógica pero débil, lo que sugiere que no todos los descuentos reducen el beneficio (-0.26).  
Por ejemplo, si se aplica un descuento del 15% a un producto premium que tiene un alto margen de beneficio, aunque el descuento reduce el precio, sigue siendo rentable porque el margen inicial es suficiente para absorber el descuento
sin generar una pérdida significativa. Para mejorar la rentabilidad, se analiza cómo cada nivel de descuento afecta los beneficios en diferentes tipos de productos. Los productos con mayor margen pueden tolerar descuentos sin afectar tanto el beneficio, mientras que los productos de bajo margen quizás deban recibir descuentos mínimos o promociones alternativas


## Análisis de las categorías más relevantes

### Tipo de cliente
El segmento de nuestros clientes que mayor número de ventas nos ha proporcionado son los consumidores que abarcan algo más de la mitad de las ventas (50,58%),
En segundo lugar los corporativos (30.73%) y por último "home office" (18.70%).

### Estado
Se separan por una parte los 10 estados con mayores contribuciones y los 10 estados con menores contribuciones para las ventas de la empresa.

Los diez estados con mayor contribución lo encabeza el estado de Califronia (30.71%), NY (16.26%) Y Texas (11.25%). El resto de estados como Washintong, Indiana, Pennsylvania, Virginia o Ohaio tienen una contribución menor del &% a nuestras ventas. (porcentaje en base a las 10 mejores estdos) 
Los diez estados con peores contribuciones son Louisiana(17%), Missisippi(12%), Sur Dakota(11.%), New Mexico(11,50%), Nebraska(11,47%), Miane, Lowa y Kansas.
La diferencia entre el mejor estado (observando el porcentaje del total) y el peor estado es de un 20%, siendo California (20,84%) el que más acumula las ventas seguido de NY (11,04%) frente a estados como Montana, Maine o Nebraska con un 0,17% del total de ventas. 

No se le ha prestado especial interés a hacer un análisis geográfico de ventas dado que estas diferencias pueden darse por factores no abarcables por la empresa como el tamaño o densidad de población del estado, por lo tanto, a un estado con más población como NY se le venderá más que a un estado de menor como Montana.

### Región
No se han observado diferencias significativas en las ventas según la región. 
El oeste de EEUU recoge el 34.57% de nuestras ventas.
El este 29.52 de las ventas.
El centro de la región el 21,81%.
El sur el 17,09%.

### Category
Tampoco se observaron diferencias significativas entre el porcentaje acumulado de ventas según la categoría de nuestros productos, siengo techology el que se lleva un porcentaje mayor de 36.38% y Furniture y Office Suplies con alrededor de un 30% de ventas.

### Subcategory
Los productos estrellas de la empresa son Chairs (14,93%) Phones (14.62%) y Binders (10,17%)
Sin embargo observamos subcategorías de productos que no son tan interesentes en cunato a ventas aunque se observó posteriormente que alguno de estos artículos como arte, dejaban grandes ebneficios por lo que si  sería interesante seguir vendiendolos aunque no acumulen un alto porcentaje de ventas.
Bookcases, Appliances, Furnishings, Pper, Supplies, Art y Evelopes, Labels y Fasterner recogen un rango entre el 6% y el 0,14% de las ventas.

Además, al segmentar estas subcategorías por tipo de cliente, se apreció que no influye el tipo de cliente 
en el producto, por lo que todos los clientes de la empresa está igualmente interesados o no interesados en los mismos productos.

### Descuento
    Se hizo un análisis por categoría de descuento en función de las ventas.
De esta manera se observó que la mayoría de nuestras ventas 47,36% no tienen ningún tipo de descuento. 
El 33, 28% de las ventas tienen un descuento del 0,2.
El 5% de las ventas un descuento del 0,4
Otro 5% de las entas iteenn un descuento del 0,3.

Se observa unos descuentos aplicados de manera atípica ya que corresponden entre al 2-0,24% de nuestras ventas
del 0,5, 01, 015, o 0,32%



## Recomendaciones basadas en los resultados obtenidos
### Estrategia para los descuentos:
-Analizar los descuentos extremos: Investigar las transacciones con descuentos muy altos para entender las razones detrás de estos valores (por ejemplo, promociones especiales, descuentos por volumen, etc.) y evaluar su impacto en la rentabilidad.
-Evaluar la efectividad de los descuentos bajos y nulos: Dado que muchos descuentos son bajos o inexistentes, podrías evaluar si los descuentos están aplicados estratégicamente o si sería conveniente ajustar la política de descuentos para aumentar su efectividad en impulsar las ventas.
### Beneficio:
-Evaluar las transacciones con beneficios negativos: Dado que existen algunas transacciones con pérdidas significativas, podría ser útil revisar los productos o servicios asociados a estas transacciones para identificar posibles causas (costos altos, precios bajos...
-Analizar las transacciones de alto beneficio: Las transacciones con beneficios muy altos podrían revelar oportunidades para optimizar la rentabilidad en otros productos o áreas de negocio.
-Identificar y analizar las transacciones con márgenes negativos o bajos para entender qué factores contribuyen a estas pérdidas.
### Costo de producción.
-Investigar las transacciones de alto costo para entender si hay formas de reducir esos costos.
-Evaluar la viabilidad de los productos con costos consistentemente altos, ya que pueden estar afectando la rentabilidad general.
-Revisar las transacciones de bajo costo (cercanas a la moda y la mediana) para ver si representan productos populares que quizás podrían estandarizarse o aumentarse en producción.
-Evaluación de Costes: Es importante que la empresa evalúe su estructura de costes y busque maneras de reducirlos, de modo que pueda mantener precios de venta altos sin verse en la obligación de ofrecer descuentos que general pérdidas o reducen considerablemente el margen de beneficio.
### Estrategia para aumentar beneficio
- Análisis de Precio y Descuento: La empresa debería considerar si sus políticas de descuento le compensan en términos de beneficio, ya que se observa que para seguir aumentando el monto de ventas la empresa sigue asumiendo costos de producción elevados que asu vez deben ajustarse a la demanda del producto, teniendo que ofrecer descuentos altos que le generan pérdidas.
### Descuentos atípicos
- Análisis de la importancia de descuentos atípicos como 0,45 o 0,32 que se hace en un porcentaje de las ventas. 
Observar qué impacto y causa tienen.