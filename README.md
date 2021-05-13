# Lineas
## Ya vimos cómo se cargan los puntos, utilizando la clase “marker”. De manera similar se pueden crear líneas en Leaflet utilizando la clase “polyline” y sus comandos.

Una polilínea, es un segmento único de línea que incluye múltiples trazos, esto se logra proporcionando al menos dos puntos con latitud y longitud que el sistema
reconocerá como los extremos de la línea, entre más puntos ingresemos la polilínea tendrá más segmentos. 


Esta herramienta puede ser muy útil para representar fallas, ríos, o cualquier elemento cuya geometría sea lineal y conozcamos los puntos por los que pasa. 
Para esto seguiremos los siguientes pasos, de manera similar a como lo hicimos con los puntos.

``` html
<script>	
var polyline = L.polyline([[20.8338559371212,  -99.783853949970251],	[20.82574053079675,  -99.782157466282968],	[20.818320593237736,  -99.779545644823031],	
[20.81314155274011,  -99.778232293010518],	[20.808481817965063,  -99.776737886182715],	[20.803823725591378, -99.774875972833541],	[20.793302601443912,  -99.770043621075345],
[20.788819713020807,  -99.767631637171618],	[20.78329324063424,  -99.766684789579017],	[20.775524869070892,  -99.764624085463765],	[20.76689556449557,  -99.761824239652626]], 
{color: 'red',weight:8}).addTo(map);
 </script>
```

### Al ejecutar en tu navegador deberías tener algo como esto.

![screenshot](https://raw.githubusercontent.com/sampach95/Lineas/master/img/lineas.png )

Siguiente Tutorial https://github.com/sampach95/Poligonos


Haz click en el siguiente enlace para volver a la pagina inicial
https://github.com/sampach95/ComoCrearMapasEnLaWebConLeaflet
