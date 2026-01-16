Proyecto Dashboard con Excel
Descripci�n
Ejercicio final del m�dulo de Dashboard & Análisis de Datos del master Data Analytic, en el que se ha creado un Dashboard para la compañía IberFarma en el que se analiza su cierre del año 2025 y se analiza el mercado de Rinitis Alérgica en el que compite.
Estructura
En el repositorio se encuentra el excel que contiene el dashboard que está formado por las siguientes pestañas:
- Datos
- Mapeos
. Tablas Dinámicas
- Dashboard
Requisitos
Para poder llevar a cabo el proyecto se han necesitado las siguientes herramientas:
* Excel
* GitHub
Limpieza y Transformación de Datos
Para poder llevar a cabo este proyecto ha sido necesario trabajar los datos originales transformándolos primero a tabla para poder trabajar más eficazmente y depurándolos después para poder obtener los datos correctos.
Se han creado variables nuevas (identificadas con la palabra "Final" en el nombre) para todos aquellas variables que necesitaban algún ajuste, como por ejemplo Principio Activo_Final (Si venía vacío el campo se buscaba el nombre del producto en la pestaña maestro y se le asignaba)
En el caso de las variables de euros y unidades, se han completado todos los campos vacios, asumiendo que el precio es siempre el mismo, para ello, en el caso de las unidades se ha formulado para que en caso de estar el campo vacío se calculara el valor correspondiente dividiendo la venta en euros entre el precio, y para los valores incompletos de las ventas, se ha multiplicado el precio por las unidades.
En la pestaña Tablas dinámicas, se han creado nuevas variables necesarias para el análisis como por ejemplo, los % Crecimiento (% Crec) y las cuotas de mercado (% MS)
Resultados y conclusiones:
En la pestaña Dashboard, se puede encontrar un informe dinámico para poder hacer el análisis tanto en Euros como Unidades.
En la primera parte podemos encontrar la información específica de nuestra compañía que sólo está disponible en Euros
y a continuación, podemos encontrar la información del mercado en el que competimos. Aquí tenemos disponible información de los competidores, de los productos, de los canales de venta, de las moléculas y de las presentaciones disponibles para cada producto.
Toda la información refente al mercado puede filtrarse por compañía, regiones y molécula para llevar a cabo un análisis más profundo.

En el caso de nuestra compañía podemos ver que ha cerrado 2025 con un crecimiento por encima del mercado con un 7,0%.

Tal y como se ve en la gráfica de evolución de ventas compañía, trabajamos en un mercado con mucha estacionalidad en los meses comprendidos entre Marzo y Junio.

Competimos en un mercado mayoritariamente de canal farmacia aunque el canala online ha crecido ligeramente en 2025

 Autor
Lourdes Martines Diaz


