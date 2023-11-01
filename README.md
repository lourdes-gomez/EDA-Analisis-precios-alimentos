# EDA-Analisis-precios-alimentos


1.INTRODUCCIÓN
	Contexto del proyecto.
	La acusada inflación de los últimos años plantea la necesidad de analizar el panorama de precios de distintos supermercados del país para lograr un conocimiento más detallado sobre el posicionamiento de los precios y su tendencia.
	Objetivo del proyecto.
	Detectar qué supermercado es más económico y para cada categoría de producto (carnes ,pescados, frutas… etc.) qué supermercado ofrece precios más económicos
	Alcance del proyecto.
	En este análisis se van a utilizar datos de los supermercados Día, Mercadona y Carrefour de los años 2020 y 2023. Y va a comprender las categorías de carne, pescado, frutas y verduras y aceite.

2. RECOLECCIÓN DE DATOS
	Fuentes.
	Los datos están extraídos de las web de:
	Datamarket, 
	Kaggle, 
	Ministerio de agricultura pesca y alimentos,
	Foodretail,
	Mercadona,
	Dia,	
	Carrefour

	Descripcion de datos.
	Los datos de datamarket y kaggle son datasets de formato csv, los datos del ministerio son archivos Excel, de foodretail he extraído texto y de las web de Mercadona, Dia y Carrefour he extraído precios.

2. EXPLORACION Y LIMPIEZA DE DATOS.
	Para ver la información relevante que podemos extraer de las tablas de datos se emplea la herramienta Pandas de Python. Se decide filtrar los productos por categorías y supermercados, compararlos y hacer gráficos.
	Para los datos de la web, se crean nuevas tablas de datos con los valores extraídos.

4. RESULTADOS.
	Se detecta que los supermercados han subido los precios en los últimos años, especialmente el aceite y que las frutas y verduras son los alimentos más económicos. Se aprecian diferencias de precio de unos supermercados a otros según qué categoría de producto. 
	Para la cesta típica se detecta el supermercado más económico y el ahorro en porcentaje de cesta y ahorro anual. En cuanto a el ahorro máximo posible (comprando cada producto en el supermercado más barato) se detecta que no hay una gran diferencia en el ahorro respecto a comprarlo todo en el mismo supermercado.
	
5.CONCLUSIONES.
	Resumen.
	Mercadona es el supermercado más barato para la cesta típica, seguido de día y Carrefour. En precios mínimos todo el mercado está bastante igualado encontrando productos al mismo precio. Para productos más caros se detecta más variabilidad en el precio, siendo ahí donde puede optimizarse el ahorro. Siguiendo la estrategia planteada se consigue un ahorro de aproximadamente -395€ al año
	En cuanto a las categorías, Día es el más económico para carnes y frutas y verduras, mientras que en pescado destaca Carrefour y Mercadona en el aceite. De acuerdo al estudio puedes ahorrar hasta un 73% comprando frutas y verduras y 13% en carne en Día y un 45% comprando aceite en Mercadona. En cuanto al pescado, Carrefour ofrece precios un 29% más económicos de media.
	
	Limitaciones del estudio.
	Tan solo se analizan cuatro categorías, no todos los productos disponibles, por lo tanto, los resultados solo son válidos para las hipótesis aquí planteadas y no extrapolables a otros productos y/o categorías.

