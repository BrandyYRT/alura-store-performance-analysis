Análisis de Tiendas Online - Proyecto de Data Science
Descripción del Proyecto
Este proyecto analiza el rendimiento de 4 tiendas online para determinar cuál debería ser vendida, basándose en datos de ventas, calificaciones de clientes, precios y categorías de productos.
Objetivo: Identificar la tienda con peor rendimiento financiero y de satisfacción del cliente para recomendar su venta.

Problema de Negocio
Una empresa posee 4 tiendas online y necesita vender una de ellas. Se requiere un análisis basado en datos para tomar la decisión correcta considerando:

Ingresos netos (ventas - costos de envío)
Satisfacción del cliente (calificaciones)
Mix de productos (categorías vendidas)
Rentabilidad por categoría


Datos Utilizados
El análisis se basa en 4 datasets con información de ventas:

tienda.csv - Tienda 1
tienda2.csv - Tienda 2
tienda3.csv - Tienda 3
tienda4.csv - Tienda 4

Estructura de los datos:
Columna - Tipo - Descripción
Producto - Texto - Nombre del producto
Categoría del Producto - Texto - Electrodomésticos, Electrónicos, Muebles, Juguetes, Deportes
Precio - Numérico - Precio en COP (pesos colombianos)
Costo de envío - Numérico - Costo de envío en COP
Fecha de Compra - Fecha - Fecha de la transacción
Vendedor - Texto - Nombre del vendedor
Lugar de Compra - Texto - Ciudad
Calificación - Entero - Calificación de 1 a 5 estrellas
Método de pago - Texto - Forma de pago utilizada
Cantidad de cuotas - Entero - Número de cuotas
lat / lon - Numérico - Coordenadas geográficas
Total de registros: aproximadamente 2,359 ventas por tienda

Metodología

Exploración de Datos (EDA)

Verificación de datos faltantes
Análisis de tipos de datos
Estadísticas descriptivas


Análisis Financiero

Cálculo de ingresos netos por tienda
Comparación de precios promedio
Análisis de costos de envío


Análisis de Satisfacción del Cliente

Distribución de calificaciones (1-5 estrellas)
Porcentaje de reseñas negativas
Identificación de patrones


Análisis de Categorías

Ventas por categoría de producto
Identificación de productos de alto valor (electrodomésticos)


Visualización de Resultados

Gráficos comparativos
Identificación de insights clave




Resultados Principales
Ingresos Netos por Tienda
Tienda 1: $1,089,502,500 - Primer lugar
Tienda 2: $1,056,858,400 - Segundo lugar
Tienda 3: $1,039,503,000 - Tercer lugar
Tienda 4: $983,058,300 - Cuarto lugar
Diferencia: Tienda 4 genera $106 millones MENOS que Tienda 1

Satisfacción del Cliente
Tienda 3: 4.05 estrellas - 75.9% reseñas buenas (4-5 estrellas) - 15.9% reseñas malas (1-2 estrellas)
Tienda 2: 4.04 estrellas - 75.6% reseñas buenas - 15.5% reseñas malas
Tienda 4: 4.00 estrellas - 74.3% reseñas buenas - 16.8% reseñas malas
Tienda 1: 3.98 estrellas - 73.6% reseñas buenas - 17.2% reseñas malas

Análisis de Categorías - Electrodomésticos
Los electrodomésticos son productos de alto valor y generan más ingresos.
Tienda 1: 312 electrodomésticos vendidos - 13.2% del total
Tienda 2: 305 electrodomésticos vendidos - 12.9% del total
Tienda 3: 278 electrodomésticos vendidos - 11.8% del total
Tienda 4: 254 electrodomésticos vendidos - 10.8% del total
Hallazgo: Tienda 4 vende 58 electrodomésticos MENOS que Tienda 1

Recomendación Final
VENDER LA TIENDA 4
Justificación:

Peor rendimiento financiero

Genera $106 millones menos que la mejor tienda (23% menos)
Ingresos netos más bajos de las 4 tiendas


Mezcla de productos poco rentable

Vende menos electrodomésticos (productos de alto valor)
58 unidades menos que Tienda 1


Satisfacción del cliente media-baja

Segunda peor en satisfacción (16.8% de reseñas malas)
Solo mejor que Tienda 1 por 0.4%


Bajo potencial de mejora

Requeriría cambio completo de estrategia de productos
Tienda 1, aunque tiene peor satisfacción, compensa con altos ingresos y puede mejorar su servicio




Visualizaciones
El proyecto incluye 3 tipos diferentes de gráficos:

Gráfico de Barras: Comparación de Ingresos Netos
Gráficos de Barras Múltiples: Distribución de Calificaciones
Gráfico Circular: Composición de Ventas Tienda 4

Tecnologías Utilizadas

Python 3
Pandas - Manipulación y análisis de datos
Matplotlib - Visualización de datos
NumPy - Operaciones numéricas
Google Colab - Entorno de desarrollo
