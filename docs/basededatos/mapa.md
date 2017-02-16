#Mapa
</br>

La representación cartográfica de los elementos almacenados en la Base de Datos IDErioja, se realiza sobre un visualizador geográfico desarrollado con medios propios, a partir de la librería Javascript de mapas *[OpenLayers](https://openlayers.org/)* (software abierto).

La representación gráfica de los elementos puede variar dependiendo del sitio desde donde se haya llamado al mapa, ya que la base de datos ofrece a los administradores de la misma, la posiblidad de configurar la simbolización de los elementos.

</br>
![Visualizador geográfico](/img/basededatos_mapa_001.jpg "Visualizador geográfico")
</br>

El visualizador utiliza el sistema geográfico de referencia UTM ETRS89 Huso 30 Norte, que es el [Sistema Geodésico de Referencia](https://www.iderioja.larioja.org/ver_docuweb_inline.php?codigo=61) oficial en España.

</br>
</br>
##Información
</br>

El botón ![Botón ver datos de la capa](/img/basededatos_mapa_101.jpg "Botón ver datos de la capa") permite examinar los datos asociados a un elementos geográfico determinado.

Una vez seleccionado el botón, y antes de elegir el elemento a interrogar, es necesario indicar en la leyenda mediante un radiobotón, la capa a la que pertenece el elemento geográfico del cual queremos extraer información.

![Selección de capa](/img/basededatos_mapa_102.jpg "Selección de capa")
</br>

Una vez hecho esto se pulsa sobre el elemento geográfico elegido.

![Ventana información de capa](/img/basededatos_mapa_103.jpg "Ventana información de capa")

</br>
</br>
##Herramientas
</br>

Además de las herramientas de navegación habituales en este tipo de visualizadores: *Zoom acercar*  (![Zooma acercar](/img/basededatos_mapa_201.jpg "Zoom acercar"))  *Zoom alejar*  (![Zooma alejar](/img/basededatos_mapa_202.jpg "Zoom alejar"))  *Zoom extensión* (![Zoom extensión](/img/basededatos_mapa_203.jpg "Zoom extensión"))  *Zoom ventana*  (![Zoom ventana](/img/basededatos_mapa_204.jpg "Zoom ventana")) y *Desplazamiento* (![Desplazamiento](/img/basededatos_mapa_205.jpg "Desplazamiento")), el botón ![Botón ir](/img/basededatos_mapa_206.jpg "Botón ir") ofrece al usuario la posibilidad de ubicarse en un punto del mapa a partir de una *coordenada*, una *dirección postal* o una *referencia catastral*.

Como complemento, el visualizador ofrece las siguientes herramientas y funciones:  

- ![Botón captura de coordenadas](/img/basededatos_mapa_207.jpg "Botón captura de coordenadas") Captura de coordenadas:  
  Una vez seleccionada esta herramienta, pulsando sobre el mapa se obtiene el par de coordenadas correspondientes al punto elegido ![XY de un punto](/img/basededatos_mapa_208.jpg "XY de un punto").  
  
- ![Botón medición de distancias](/img/basededatos_mapa_209.jpg "Botón medición de distancias") Medición de distancias:  
  Para medir una distancia, se debe ir pulsando sobre en aquellos puntos que representen los vértices de la polilínea a medir. Según se va efectuando la operación, el sistema ofrece información de la distancia medida. Se finaliza la medición con un '*doble clic*'  ![Medición de distancias](/img/basededatos_mapa_210.jpg "Medición de distancias").  
  
- ![Botón medición de áreas](/img/basededatos_mapa_211.jpg "Botón medición de áreas") Medición de áreas:  
  Para medir un área, se debe ir pulsando sobre en aquellos puntos que representen los vértices de la superficie que se quiere medir. A medida que se se va realizando la operación, el sistema ofrece información del área medida. Se finaliza la medición con un '*doble clic*'  ![Medición de áreas](/img/basededatos_mapa_212.jpg "Medición de áreas").  
  
- ![Botón gráficos](/img/basededatos_mapa_213.jpg "Botón gráficos") Gráficos:  
  Esta herramienta permite trazar sobre el mapa gráficos regulares e irregulares  
  </br>
  ![Opciones gráficos](/img/basededatos_mapa_214.jpg "Opciones gráficos")  
  </br>
  configurando sus propiedades.  
  </br>
  ![Propiedades gráficos](/img/basededatos_mapa_215.jpg "Propiedades gráficos")  
  </br>
  Los elementos dibujados se pueden guardar en formato [GeoJSON](http://geojson.org/), por lo que pueden ser cargados y reutilizados posteriormente.  
  
- ![Botón etiquetas](/img/basededatos_mapa_216.jpg "Botón etiquetas") Etiquetas:  
  De forma similar a los gráficos, también es posible añadir al mapa etiquetas personalizadas.  
  Una vez seleccionada la herramienta, es necesario pulsar sobre el mapa en el punto en el que se quiere anclar la etiqueta. Hecho esto, se ofrece al usuario una pantalla para configurar las propiedades de simbolización del texto.  
  </br>
  ![Propiedades etiquetas](/img/basededatos_mapa_217.jpg "Propiedades etiquetas")
  
- ![Google Street View](/img/basededatos_mapa_218.jpg "Google Street View") Google Street View:  
  El Visualizador ofrece la posiblidad de realizar consultas visuales utilizando la utilidad *"Google Street View"*.  
  </br>
  Después de seleccionar el botón, es necesario pulsar sobre el mapa. Si *Google* dispone de información asociada para ese entorno, se abre una nueva ventana que permite moverse haciendo uso de las funcionalidades de esta herramienta. La ventana incluye unos controles propios para optimizar la consulta: *Rotación*, *Velocidad*, *Zoom*.  
  </br>
  ![Ventana Google Street View](/img/basededatos_mapa_219.jpg "Ventana Google Street View")  

</br>
</br>
##Fondos
</br>

Cuando se inicia el visualizador geográfico, este presenta por defecto un fondo cartográfico de referencia con información cartográfica de La Rioja, que en los niveles de zoom más alejados incluye información visual de relieve.

Este fondo cartográfico se denomina *"Mapa Base IDErioja"*.

![Mapa Base IDErioja](/img/basededatos_mapa_301.jpg "Mapa Base IDErioja")

</br>
En algunas ocasiones es necesario utilizar otro tipo de referencias fotográficas o topográficas.

A través de la pestaña *"Fondos"*, es posible seleccionar otro fondo cartográfico entre una variada colección:

![Fondos cartográficos](/img/basededatos_mapa_302.jpg "Fondos cartográficos")

Cuando se selecciona un nuevo fondo cartográfico, o pulsando sobre el fondo activo, es posible configurar su nivel de transparencia.

</br>
</br>
##Otras capas
</br>
Una de las opciones que ofrece el visualizador geográfico, es la de incorporar otras capas capas geográficas existentes en la Base de Datos IDErioja.

Esta operación se realiza accediendo a la pestaña *"Otras Capas"*.

![Otras capas](/img/basededatos_mapa_401.jpg "Otras capas")

</br>
La pantalla incluye un buscador que permite rastrear un texto determinado entre toda la oferta de información.

![Buscar capa](/img/basededatos_mapa_402.jpg "Buscar capa")

Es necesario señalar que la oferta de capas es variable para cada configuración del visualizador, pudiendo ser modificada por el Administrador del Sistema.

</br>
</br>
##Servicios OGC:WMS
</br>

El visualizador geográfico IDErioja, es compatible con los Servicios de Mapas WEB (WMS) definidos por el [Open Geospatial Consortium(OGC)] (http://www.opengeospatial.org/standards/wms).

Esto permite incorporar al visualizador información cartográfica procedente de cualquier Servico WMS que ofrezca información en el Sistema Geográfico de Referencia UTM ETRS89 30N [EPSG:25830](https://epsg.io/25830).

Para facilitar el trabajo de localización de servicios WMS al usuario, existe un catálogo de servicios WMS muy amplio cuyo funcionamiento ha sido testeado con el visualizador, que se ofrece al usuario a través de la pestaña *"Servidores"*.

![Servidores WMS](/img/basededatos_mapa_501.jpg "Servidores WMS")

</br>
Para mayor comodidad el catálogo de servidores está organizado en:

- Servidores de la C.A. de La Rioja
- Servidores nacionales
- Servidores regionales
- Servidores locales
- Servidores técnicos de apoyo a la edición
- Servidores Intranet del Gobierno de La Rioja

Una vez se ha seleccionado un servidor, el visualizador lanza una petición de información al servicio con el fin de conocer las capas geográficas ofertadas. Una vez recibida la información, le presenta al usuario una relación de las mismas para que este seleccione las de su interés.

![Capas WMS](/img/basededatos_mapa_502.jpg "Capas WMS")

</br>
Una vez realizada la selección, la información procedente del Servico de Mapas WMS se incorpora al visualizador, siendo refrescada tras cada operación de navegación.

Si se activa el radiobotón de la leyenda para la capa procedente de un servicio WMS, la operación de solicitar datos de la capa  ![Botón ver datos de la capa](/img/basededatos_mapa_02.jpg "Botón ver datos de la capa") , lanza contra el servidor una petición *"GetFeatureInfo"* que devuelve la información asociada al punto seleccionado.

En el ejemplo siguiente, el Servicio WMS de la D.G. del Catastro devuelve una url que apunta a la información catastral de la parcela seleccionada.

![GetFeatureInfo](/img/basededatos_mapa_503.jpg "GetFeatureInfo")

</br>
En caso de que el Servicio WMS que se quiere consultar no estuviera incluido en el catálogo, la pestaña *"Servidores"* ofrece la posibilidad de introduccir manualmente la url del servicio. En este caso el usuario debería asegurarse de antemano que el servicio a incluir es compatible con el sistema geográfico del visualizador.

</br>
</br>
##Otras opciones
</br>

Repartidas por el espacio de pantalla, el visualizador geográfico ofrece otras opciones:

- ![Recarga el mapa](/img/basededatos_mapa_601.jpg "Recarga el mapa")  Recarga el mapa, restaurando sus valores iniciales.
- ![Información legal](/img/basededatos_mapa_602.jpg "Información legal")  Muestra la información Legal.
- ![Imprime el mapa](/img/basededatos_mapa_603.jpg "Inmprime el mapa") Imprime el mapa (no se imprimen etiquetas ni gráficos).
- ![Ayuda](/img/basededatos_mapa_604.jpg "Ayuda")  Ayuda.
- ![Colabora con IDErioja](/img/basededatos_mapa_605.jpg "Colabora con IDErioja")  Colabora con IDErioja. Esta función permite enviar a la Sección de SIG y Cartografía un comentario o sugerencia y acompañarla de una imagen.
- ![Salir](/img/basededatos_mapa_606.jpg "Salir")  Salir.

</br>
MAPA GUÍA

La pestaña *"Mapa Guía"* despliega un pequeños mapa de referencia que permite un desplazamiento casi inmediato pulsando sobre un punto del mismo.

![Mapa guía](/img/basededatos_mapa_607.jpg "Mapa guía")

</br>
COORDENADAS Y ESCALA

La información del visualizador se completa con una escala gráfica y con información de las coordenadas del puntero.

![Escala gráfica](/img/basededatos_mapa_608.jpg "Escala gráfica")

</br>
*NOTA: Puede encontrar más información de detalle sobre el funcionamiento de las herramientas de  navegación y posicionamiento, la edicición de gráficos y las opciones de la leyenda, en el propio botón de ayuda del visualizador  ![Ayuda](/img/basededatos_mapa_34.jpg "Ayuda")  y en [este enlace](https://visor2.iderioja.larioja.org/lib/ayuda.php).

