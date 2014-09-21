* Los pasos seguidos para realizar la tarea: Assignment-esLODCloud fueron los siguientes:
1. B�squeda de los links activos (de los datasets espa�oles generados anteriormente del Assignment1) desde el siguiente enlace: http://es.dbpedia.org/Wiki.jsp?page=EsLODcloud
2. Mirar uno por uno todos los links de todas las paginas, y sus respectivos enlaces, asi como sus datos estad�sticos, para a�adirlos al archivo turtle.
3. Comprobar que todos los enlaces, y la informaci�n de los datasets est� realmente activa.
4. Generaci�n del SVG con parte de herramienta que se encuentra en el siguiente enlace: http://lmatteis.github.io/void-graph/
5. Por �ltimo hacer un pull request para los archivos, ttl, como el archivo png (que se genera con la herramienta del paso4).
Informaci�n t�cnica: 
He seleccionado algunas etiquetas del lenguaje, no he utilizado todas, solo las que considere importantes para definir el catalogo en cuesti�n, alguna de ellas son las siguientes:
* dcterms:title -> nombre del dataset a representar.
* foaf:homapage -> define la p�gina principal donde se puede acceder al conjunto de datos.
* void:subset -> conjunto de otros datos con los que se relaciona, el dataset en cuesti�n.
* dcterms:contributor -> se indica tanto el author como el mainteiner del dataset.
* void:triples -> indica el tama�o de datos que contiene el dataset, es un dato importante dentro de las estad�sticas del mismo.
