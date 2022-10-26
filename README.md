# MMMMMM6
# PROYECTO  GAMA

La consigna consiste en desarrollar una aplicación en Python, que tome los datos de alguna ó algunas páginas web, haciendo Web craping, guardando los datos recolectados en una base de datos.
Luego hacer una aplicación que muestre los datos almacenados, pero que también permita manipular los mismos.
Por último, con dicha información, realizar un informe. Este informe puede ser simple a través de la comparación entre elementos recolectados de las diferentes fuentes, estadísticos sobre las series de los datos o cualquier tipo de análisis del tipo Big Data o
Machine Learning, como regresiones, proyecciones, etc.

EJEMPLO: 
Solo a los fines de proponer un ejemplo que amplíe la consigna, imaginemos que tomamos páginas como https://pypi.org/project/investpy/ ó https://es.finance.yahoo.com/quote/TEF?p=TEF&.tsrc=fin-srch ó https://www.bolsamadrid.es/esp/aspx/Mercados/Precios.aspx?indice=ESI100000000 ó de Gobiernos Abiertos.
Como bien sabemos las páginas web son documentos estructurados  formados por una jerarquía de elementos. Así que luego de elegir la página, el siguiente paso consiste en identificar correctamente el elemento o elementos que contienen la información deseada.
Luego hay que descargar el contenido de la página utilizando la librería requests.
El contenido de la página obtenido en el paso anterior será el que utilicemos para crear la «sopa», esto es, el árbol de objetos Python que representan al documento HTML. 
Ahora estamos en condiciones de buscar en el árbol y obtener los objetos que contienen la información y datos que necesitamos.
Una vez obtenidos los datos los guardarán en una base de datos. La cual permitirá manipular los mismos haciendo modificaciones o eliminando registros.
Por último, realizar algún informe.
