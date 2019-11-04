<p align="center">
  <strong>Under development</strong>
</p>

<p align="center">
  <img src="https://github.com/joseignaci/Recursos-Informacion-Geografica/blob/master/recursos_abiertos_tig_en_github.jpg" alt="Recursos abiertos de Información Geográfica">
</p>

## Presentación
El rápido crecimiento de las Tecnologías de la Información la Comunicación TIC obliga hoy en día a que un gran número de profesionales necesiten manejar __Información Geográfica__ para desarrollar, presentar y publicar sus estudios en los ámbitos más diversos (medio ambiente, urbanismo, gestión de riesgos, sociología, salud, marketing…), pero los autores no siempre conocen las herramientas que están a sus disposición, al no ser la Información Geográfica su especialidad.

Basándome en la experiencia de casi 20 años compartiendo recursos y divulgando conocimiento TIG con [Nosolosig](http://www.nosolosig.com) e inspirado por el artículo de las investigadoras de la Universidad de Extremadura (España) __Elia Quirós__ y __María Eugenia Polo__ [Recursos abiertos de información geográfica para investigación y documentación científica][faeea2a2], publicado en la «*Revista Española de Documentación Científica*», os presento una serie de recursos abiertos de Información Geográfica.

Contribuciones, correciones o comentarios son bienvenidos

  [faeea2a2]: https://doi.org/10.3989/redc.2018.3.1512 "Recursos abiertos de información geográfica para investigación y documentación científica"



## Estructura
- [Introducción](#introduccion)
- [Cartografía local](#cartografia-local)
- [Cartografía regional](#cartografia-regional)
- [Cartografía nacional](#cartografia-nacional)
- [Cartografía Transnacional](#cartografia-transnacional)
- [Cartotecas en universidades, centros públicos y privados](#spatial-sql)
- [Información Geográfica Voluntaria](#informacion-geografica-voluntaria)
- [Software](#software)
  - [Software de Sistemas de Información Geográfica -SIG-](sistemas-informacion-geografica-sig)
  - [Teledetección](teledeteccion)
  - [LIDAR, fotogrametría](lidar-fotogrametria)
  - [Metadatos](metadatos)
  - [Bases de datos, ETL, otros](bases-de-datos-etl-otros)
- [Creación de cartografía](#web-gis)
- [Formación, aprendizaje](#formacion-aprendizaje)
  - [Libros](libros)
  - [Listas, foros, blogs](#etl)
  - [Revistas indexadas](revistas-indexadas)

## INTRODUCCIÓN
Una primera versión de esta lista de recursos se publicó en Nosolosig [Recursos abiertos de Información Geográfica para la investigación](http://www.nosolosig.com/articulos/1061-recursos-abiertos-de-informacion-geografica-para-la-investigacion), fiel al contenido del artículo citado anteriormente. El objetivo de compartir estos recursos en GitHub es facilitar el mantenimiento, actualización y modificaciones de los recursos entre todos. 

Los recursos presentados tienen principalmente licencias libres, por ejemplo Creative Commons, aunque en algunos casos he incluido software o servicios privados pero gratuitos.

## CARTOGRAFÍA LOCAL
### España
- IDEE locales: http://www.idee.es/web/guest/local Infraestructuras de Datos Espaciales de entidades locales de España

## CARTOGRAFÍA REGIONAL

### España
- [IDEE autonómicas](http://www.idee.es/web/guest/autonomico) Infraestructuras de Datos Espaciales de autonomías de España. Se pueden encontrar IDE por autonomía o por tema (hidrografía, geología, cartografía temática, etc.)

Las **institutos oficiales de cartografía** en las autonomías españolas son:
- [Instituto Cartográfico y Geológico de Cataluña](http://www.icgc.cat/es/)
- [Instituto Cartográfico de Valencia](http://www.icv.gva.es/ca/inicio)
- [Instituto de Estadística y Cartografía de Andalucía](http://www.juntadeandalucia.es/institutodeestadisticaycartografia)
- [Instituto Geográfico de Aragón](http://gobierno.aragon.es/DepartamentosOrganismosPublicos/Institutos/IGEAR)

## CARTOGRAFÍA NACIONAL

### España
- [Infraestructuras de Datos Espaciales de España](http://idee.es/)
- [Centro de descargas del CNIG](http://centrodedescargas.cnig.es/CentroDescargas/)
- [Sistema integrado de Información del Agua (SIA)](http://www.mapama.gob.es/es/agua/temas/planificacion-hidrologica/sia-/infodescargas.aspx)
- [Mapa Forestal de España](http://www.mapama.gob.es/es/biodiversidad/servicios/banco-datos-naturaleza/informacion-disponible/mfe50.aspx) a escala 1:50.000 (MFE50); es la cartografía de la situación de las masas forestales, realizada desde el Banco de Datos de la Naturaleza; en formato shape y .pdf
- [Sistema de Información Geográfica de Parcelas Agrícolas (SIGPAC)](http://sigpac.mapa.es/fega/visor/)
- [Instituto Geológico y Minero de España](http://www.igme.es/)
- [Sede Electrónica del Catastro](http://www.sedecatastro.gob.es/) (España) Se puede descargar información cartográfica y alfanumérica, servicios web, formatos INSPIRE, datos estadísticos
- [Archivo topográfico nacional de lindes (ATNL)](http://atnl.coigt.com/#/auth) por el Ilustre Colegio Oficial de Ingeniería Geomática y Topográfica (COIGT)
- [AEMET OpenData](http://www.aemet.es/es/datos_abiertos/AEMET_OpenData) es un API REST a través del cual se pueden descargar gratuitamente los datos explicitados en el Anexo II de la resolución de 30 de diciembre de 2015 de Agencia Estatal de Meteorología
- [Instituto Nacional de Estadística](http://www.ine.es/welcome.shtml)

<small>[_ir arriba_](#Estructura)</small>

## CARTOGRAFÍA TRANSNACIONAL
- [IDEs transfronterizas](http://www.idee.es/web/guest/transfronterizo) Proyectos de Infraestructuras de Datos Espaciales que muestran información geográfica de distintos países limítrofes
- [EuroGlobalMap](https://eurogeographics.org/products-and-services/open-data/) Datos topográficos y abiertos a escala 1:1.000.000 que cubre 45 países y territorios en Europa; pensado para funcionar como mapas base
- [European Environment Agency (EEA)](https://www.eea.europa.eu/data-and-maps)
- [The European Soil Database](http://eusoils.jrc.ec.europa.eu/ESDB_Archive/ESDB_data_1k_raster_intro/ESDB_1k_raster_data_intro.html) base de datos relacionados con el suelo en Europa. Su ambición es albergar todos los datos e información de suelo relevantes a nivel europeo. Contiene una serie de recursos que se organizan y presentan de varias maneras: conjuntos de datos, servicios / aplicaciones, mapas, documentos, eventos...
- [Global Administrative Areas (GADM)](http://www.gadm.org/) Iniciativa privada que recopila (o intenta) todos los límites administrativos de los países del mundo (niveles nacional, regional, local)
- [Natural Earth](http://www.naturalearthdata.com/downloads/)
- [FAO GeoNetwork](http://www.fao.org/geonetwork/srv/en/main.home) Mapas interactivos, imágenes satelitales y bases de datos espaciales relacionadas mantenidas por la FAO y sus socios, con el fin de mejorar el acceso y el uso de Información Geográfica
- [United Nations Environment Programme](http://geodata.grid.unep.ch/index.php) Los datos ofciales usados por el Progrma Ambiental de las Naciones Unidas (UNEP). Más de 500 variables ofrecidas en datos o mapas, con temas como demografía, deforestación, clima, etc.
- [WorldMapper](https://worldmapper.org/)
- [Geosur](https://www.geosur.info) Su objetivo es promover el uso y diseminación de la información geográfica en América Latina y el impulso de las Infraestructuras de Datos Espaciales


## CARTOTECAS EN UNIVERSIDADES, CENTROS PÚBLICOS Y PRIVADOS
- [OldMapsOnline](http://www.oldmapsonline.org/)
- [David Rumsey Map Collection](http://www.davidrumsey.com/)
- [Ibercarto](https://sge.org/ibercarto/) o Grupo de Trabajo de Cartotecas Públicas Hispano-Lusas; aquí podrás encontrar un directorio de cartotecas de España y Portugal. Muy interesante
- [Biblioteca Digital Hispánica](www.bne.es/es/Catalogos/BibliotecaDigitalHispanica/Inicio/) el portal libre y gratuito de documentos digitalizados de la Biblioteca Nacional de España, con una importante colección de mapas: más de 12.000 registros entre material cartográfico impreso y manuscrito
- [Biblioteca Digital de la Real Academia de la Historia](http://bibliotecadigital.rah.es/dgbrah/es/consulta/registro.cmd?id=15911)



## INTERFACES DE VISUALIZACIÓN
- [Google Maps](https://www.google.es/maps)
- [Google Earths]( https://www.google.es/intl/es/earth/index.html)
- [Google Street View](https://www.google.es/intl/es/streetview/)
- [Indoor Google Maps](https://www.google.com/maps/about/partners/indoormaps/)
- [Bing Maps](https://www.bing.com/maps?FORM=Z9LH3)
- [ArcGIS Earth](http://www.esri.com/software/arcgis-earth)
- [Nasa WorldWind](https://worldwind.arc.nasa.gov/)
- [Marble](https://marble.kde.org/index.php)
- [IBERPIX](http://www.ign.es/iberpix2/visor/) Visor de cartografía y ortofotos del Instituto Geográfico Nacional (IGN) de España

## INFORMACIÓN GEOGRÁFICA VOLUNTARIA
- [OpenStreetmap](http://www.openstreetmap.org/)
- [Wikimapia](https://es.wikipedia.org/wiki/Wikimapia)
- [Crowdmap](https://crowdmap.com/welcome)
- [Geocaching](http://www.geocachingspain.es/)

## SOFTWARE
### Sistemas de Información Geográfica
- [gvSIG](http://www.gvsig.org)
- [QGIS](http://www.qgis.org/)
- [Spring](http://www.dpi.inpe.br/spring/)
- [uDig](http://udig.refractions.net/)
- [TerrSet](https://clarklabs.org/terrset/)
- [SAGA GIS](http://www.saga-gis.org)
- [Whitebox GAT Project](http://www.uoguelph.ca/~hydrogeo/Whitebox/)
- [MapWindow](http://www.mapwindow.org/)
- [OpenJump](http://www.openjump.org/)
- [Diva GIS](http://www.diva-gis.org/)
- [OrbisGIS](http://orbisgis.org/)
- [GeoDa](http://geodacenter.github.io/index.html)
- [OSSIM Open Source Software Image Map](https://trac.osgeo.org/ossim/)

### Teledetección
- [ILWIS](http://ilwis.itc.utwente.nl/wiki/index.php/Main_Page)
- [GRASS](http://grass.osgeo.org/)
- [SNAP de la ESA](http://step.esa.int/main/)
- [Orfeo ToolBox (OTB)](https://www.orfeo-toolbox.org/)
- [InterImage](http://www.lvc.ele.puc-rio.br/projects/interimage/)
- [OPTICKS](https://opticks.org/)


### LIDAR, fotogrametría
- [Fusion](http://forsys.sefs.uw.edu/fusion/fusionlatest.html)
- [LAStools](http://www.cs.unc.edu/~isenburg/lastools/)
- [fullanalyze](https://code.google.com/archive/p/fullanalyze/)


### Metadatos
- [Geonetwork Metadata](https://geonetwork-opensource.org/)
- [pycsw](https://pycsw.org/)
- [Geoportal de Metadatos del IGN](http://metadatos.ign.es/herramientas) Aquí encontrarás varias herramientas para la creación, edición y validación de metadatos
- [CatMDEdit](http://catmdedit.sourceforge.net/)

### Bases de datos, librerias
- [OSGeo](https://www.osgeo.org/) La *Open Source Geospatial Foundation* acoge un montón de software (algunos ya citados en esta lista); **imprescindible**
- [libLAS](https://liblas.org/)
- [GDAL](https://gdal.org/)
- [postGIS](https://postgis.net/)
- [OpenLayers](https://openlayers.org) Biblioteca de JavaScript de código abierto para publicar mapas interactivos en la web
- [Leaflet](https://leafletjs.com/) Biblioteca de JavaScript de código abierto para publicar mapas interactivos en la web
- [Cesium](https://cesiumjs.org/) Biblioteca JavaScript para crear globos terráqueos en 3D

### Visualización de datos
- [Tableau Public](https://public.tableau.com/en-us/s/) Software gratuito para crear visualizacones interactivas de datos. Permite datos espaciales
- [Power BI](https://powerbi.microsoft.com/es-es/) Visualización de datos con esta espectacular herramienta de Microsoft
- [Google Data Studio](https://datastudio.withgoogle.com/)
- [dj3](https://d3js.org/) Biblioteca JavaScript para crear gráficos dinámicos e interactivos a partir de datos

### Otros
- [Geoserver](http://geoserver.org/)
- [MapServer](http://mapserver.org/es/index.html)
- [Descarga de software del IECA](https://www.juntadeandalucia.es/institutodeestadisticaycartografia/ieagen/otrosServidores/software/index.htm)


## CREACIÓN/PUBLICACIÓN DE CARTOGRAFÍA (GIS CLOUD)
- [urbiThings](https://urbithings.com/)
- [QGISCloud](http://qgiscloud.com/)
- [InstaMaps](https://www.instamaps.cat/)
- [Polymaps](http://polymaps.org/)
- [Mapbox](https://www.mapbox.com/)
- [GeoWe](http://www.geowe.org/)
- [uMap](https://umap.openstreetmap.fr/es/)
- [MapTiler](https://www.maptiler.com/)
- [Worldmap](http://worldmap.harvard.edu/)
- [Google My maps](https://www.google.com/intl/es_ES/maps/about/mymaps/)
- [Deegree](https://www.deegree.org/)

## FORMACIÓN, APRENDIZAJE

### Glosarios y libros

- [Sistemas de Información Geográfica](http://volaya.github.io/libro-sig/) de Víctor Olaya
- [Glosario de términos geográficos y cartográficos](https://biblioteca.ua.es/es/cartoteca/glosario-a.html)
- [Diccionario de Geografía aplicada y profesional](https://www.uv.es/~javier/index_archivos/Diccionario_Geografia%20Aplicada.pdf)
- [R para profesionales de los datos: una introducción](https://www.datanalytics.com/libro_r/index.html) Aunque no está orientado a los datos espaciales, si estás interesado en aprender R echa un vistazo a este libro (inacabado) de __Carlos J. Gil Bellosta__
- [Libros TIG](http://www.nosolosig.com/libros-geo) Afortunadamente son muchos los libros que puedes encontrar para aprender Tecnologías de Información Geográfica (TIG), un gran número de ellos gratis o con licencias CC. En esta sección de Nosolosig encontrarás muchos de ellos

### Listas de correo
* Las listas de correo de RedIris son todo un clásico y aunque ya no tienen el mismo volumen de actividad que hace unos años, todavía son una excelente fuente de información y consulta. Aquí van algunas de las más importantes, pero encontrarás muchas otras
  - [Lista SIG de RedIris](http://www.rediris.es/list/info/sig.html) Lista de Sistemas de información Geográfica y Cartográfica
  - [Lista IDE de RedIris](http://www.rediris.es/list/info/idee.html) Lista de Infraestructuras de Datos Espaciales
  - [Lista fotogrametría de RedIris](http://www.rediris.es/list/info/fotogrametria.html)
- [Listas de correo de OSGeo](http://www2.osgeo.org/content/faq/mailing_lists_ES.html)
- [Listas de Geoinquietos](http://geoinquietos.org/) Los Geoinquietos son grupos de personas que se reunen para aprender y divulgar sobre geotecnologías y software libre. Hay grupos por paises y ciudades

### Revistas indexadas
- [GeoFocus. Revista Internacional de Ciencia y Tecnología de la Información Geográfica](http://www.geofocus.org/index.php/geofocus)
- [Revista Cartográfica](https://www.ipgh.org/revista-cartografica.html) publicada por el Instituto Panamenricano de Geografía e Historia (IPGH)
- [Revista CT/Catastro](http://www.catastro.meh.es/esp/ct_catastro.asp) (España)
- [Revista Mapping](http://mappinginteractivo.es/)
- [Revista de la Asociación Española de Teledetección](http://www.aet.org.es/)
- [Investigaciones Geográficas](https://www.investigacionesgeograficas.com/) editada por el Instituto Interuniversitario de Geografía de la Universidad de Alicante (España)

### Blogs
- [Blog y páginas Web sobre Tecnologías de la Información Geográfica](http://www.nosolosig.com/articulos/192-blog-y-paginas-web-sobre-tecnologias-de-la-informacion-geografica) Son muchos los blogs que puedes encontrar en Internet sobre TIG; en este enlace encontrarás una lista con casi todos ellos (última actualización en 2017), muchos para enumerar aquí.
