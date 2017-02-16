#Base de Datos
</br>

En el año 2003 *Oracle Corporation* presentó un *modelo espacial* que permitía almacenar información geográfica en su base de datos relacional.

Esta posibilidad permitió al Gobierno de La Rioja diseñar un plan de acción con tres objetivos:

* Gestión centralizada de los datos geográficos
* Corresponsabilidad en el mantenimiento de la información
* Funcionamiento en la nube

Para facilitar la gestión colaborativa, se programó una aplicación *Java* que ofrecía la posibilidad de editar y consultar la información geográfica *"on line"*.

La funcionalidad inicial se extendió posteriormente a la edición geográfica y la administración de la propia base de datos, además de la configuración de todos los servicios y contenidos web.

Para facilitar el acceso público a la información, existe un **[acceso anónimo](https://ias1.larioja.org/iderioja/ANONIMO_INSPIRE)** que permite, sin identificación previa, operar en el entorno de base de datos con los mismos datos geográficos que utiliza la Administración.

</br>
![Base de datos IDErioja](/img/basededatos_guiabasica_001.jpg "Base de datos IDErioja")
</br>

</br>
</br>
##Información General
</br>

La información contenida en la base de datos geográfica del Gobierno de La Riojase se muestra estructurada en tablas (capas).

Los elementos contenidos en ellas (registros), se presentan de forma ordenada.

La información asociada a los mismos se puede consultar alfanuméricamente o en forma de mapas, bien para el conjunto de todos los elementos de una tabla o para una selección determinada de ellos.

</br>
</br>
##Estructura del menú
</br>

El acceso a los datos geográficos se realiza a través de un menú temático de tres niveles.

</br>
![Estructura del menú](/img/basededatos_guiabasica_201.jpg "Estructura del menú")</br>
</br>

El botón **[Buscar]** permite localizar un texto a través de la página (sensible a mayúsculas/minúsculas y acentos).

Los botones **[Desplegar]** y **[Colapsar]**, muestran o esconden la estructura completa del árbol del menú.

</br>
</br>
##Navegación por la tabla
</br>

Al hacer click sobre una entrada del menú, se muestra una lista ordenada de los registros de la capa.

</br>
![Navegación por la tabla](/img/basededatos_guiabasica_301.jpg "Navegación por la tabla")
</br>

En la parte superior de la tabla existen unos botones con la siguiente funcionalidad:

</br>

**[Buscar]**:  Permite realizar una selección de los registros de la tabla que cumplan los criterios definididos:

</br>
![Filtrado de registros](/img/basededatos_guiabasica_302.jpg "Filtrado de registros")</br>
</br>

* Selección por identificación  
Se define la cadena de texto a localizar en el nombre del elemento o un rango de identificadores.
* Selección por atributos  
Se especifican una o más condiciones que tienen que cumplir los atributos de los elementos a seleccionar.  
El número y definición de los atributos varía para cada tabla conforme a su modelo de datos.
* selección espacial  
Se realiza una consulta espacial utilizando los comandos geoespaciales de la base de datos.  
Este tipo de consulta requiere mayor tiempo de procesamiento.

En la pantalla de filtrado de información también se puede definir el criterio de orden a aplicar para la presentación de resultados.

**[Recargar]**: Al pulsar este botón se recargará la información de la pantalla con la información existente en la base de
datos. Equivale a un refresco de la información mostrada.

**[Primero]**: Muestra los elementos correspondientes a la primera pantalla de la lista actual. Si la lista está situada en
su inicio, el botón se muestra inhabilitado.

**[Anteriores]**: Presenta la pantalla anterior de la lista actual. Si la lista está situada en su inicio, el botón aparece inhabilitado.

**[Siguientes]**: Presenta la siguiente pantalla de la lista actual. Si la lista está situada al final, el botón estará inhabilitado.

**[Metadatos]**: Muestra una nueva ventana con la información de los metadatos ISO19115 de la capa correspondiente a la lista de elementos presentada. Si la capa no tiene metadatos asociados en el sistema, el botón aparece inhabilitado.

![Metadatos](/img/basededatos_guiabasica_303.jpg "Metadatos")</br>
</br>

**[[Mapa]](../basededatos/mapa)**: Accede al visualizador geográfico IDERioja, para mostrar de forma gráfica en una nueva ventana, la representación cartográfica de todos los elementos de la lista.

</br>
![Mapa](/img/basededatos_guiabasica_304.jpg "Mapa")</br>
</br>

**[Exportar]**: Exporta el contenido alfanumérico de la tabla a un fichero de texto, con formato [CSV](https://es.wikipedia.org/wiki/Valores_separados_por_comas). El fichero utiliza como separador de campos el caracter *tabulador*. Este fichero puede ser abierto directamente por cualquier programa de hoja de cálculo o base de datos.

**[Tabla]**: Abre un entorno que facilita la consulta de la tabla de datos, en el cual es posible definir de una manera elástica filtros complejos.

</br>
![Tabla](/img/basededatos_guiabasica_305.jpg "Tabla")</br>
</br>

**[Imprimir]**: Salida impresa de la lista que aparece en pantalla.

**[Salir]**: Abandona la consulta de la capa.

</br>
</br>
##Consulta de datos
</br>
Para acceder a los datos contenidos en un registro, es necesario hacer *click* sobre su nombre.

La presentación de los datos se estructura mediante pestañas. El número y denominación de las pestañas varía en función del modelo de datos de la capa.

</br>
![Consulta de datos](/img/basededatos_guiabasica_401.jpg "Consulta de datos")</br>
</br>

Todos los elementos geográficos de la base de datos presentan la pestaña *"Identificación"* que contiene los datos identificativos del elemento: *identificadores* y *nombre*, junto con su definición geográfica.

Para la interpretación de su geometría se ha incrustado en la pantalla un pequeño visualizador geográfico. Pulsando sobre la imagen o en el botón **[Mapa]**, se presenta el elemento en el visualizador IDErioja, con toda su funcionalidad.

Desde la lista de registros también es posible representar un elemento sobre el visualizador geográfico, pulsando sobre el icono de mapa que se encuentra a la izquierda del nombre.

</br>
![Llamada al mapa](/img/basededatos_guiabasica_402.jpg "Llamada al mapa")</br>
</br>

El botón **[Coordenadas]**, permite ver directamente el registro `Geom` de la base de datos, en el que se almacenan las geometrías espaciales, junto con la referencia del sistema de coordenadas utilizado:

</br>
![Registro Geom](/img/basededatos_guiabasica_403.jpg "Registro Geom")
</br>

La información específica del registro se presenta ordenada a través de pestañas, intentando agrupar la información relacionada.

![Pestañas](/img/basededatos_guiabasica_404.jpg "Pestañas")
</br>

</br>
![Pestañas](/img/basededatos_guiabasica_405.jpg "Pestañas")
</br>

</br>
</br>
##Imágenes y documentos
</br>

La base de datos geográfica IDErioja, tiene la singularidad de poder asociar a sus elementos geográficos, colecciones de imágenes y de documentos con formatos variados.

Para poder consultar los elementos asociados, se han habilitado dos pestañas especiales denominadas *"Imágenes"* y *"Documentos"*. Estas pestañas solo son visibles cuando el elemento geográfico tiene imágenes o archivos asociados.

</br>
![Pestaña imágenes](/img/basededatos_guiabasica_501.jpg "Pestaña imágenes")</br>
</br>

</br>
###Imágenes
</br>

Pulsando sobre la miniatura de una imágen, se abre un carrusel que permite navegar por toda la colección.
</br>
![Carrusel de imágenes](/img/basededatos_guiabasica_502.jpg "Carrusel de imágenes")
</br>

Pulsando a su vez sobre una imagen del carrusel, se abre un visor gráfico que permite ver la imagen con toda su resolución, ampliar su nivel de detalle y descargarla.

</br>
![Visor de imágenes](/img/basededatos_guiabasica_503.jpg "Visor de imágenes")
</br>

</br>
###Documentos
</br>

De forma similiar a lo que ocurre con las imágenes, cuando un registro tiene documentos asociados, se ofrece al usuario a través de la pestaña *"Documentos"*, la posiblidad de ver el listado completo de documentos asociados, así como acceder a los mismos.

</br>
![Visor de documentos](/img/basededatos_guiabasica_504.jpg "Visor de documentos")</br>

</br>
![Visor de pdfs](/img/basededatos_guiabasica_505.jpg "Visor de pdfs")</br>
</br>

Además de archivos físicos el sistema permite asociar a los elementos geográficos de la base de datos *Urls* de Internet.

Al igual que ocurre con los atributos convencionales, las colecciones de imágenes y de documentos forman parte de la información asociada al elemento geográfico, por lo que son también accesibles a través de los distintos servicios de publicación.
