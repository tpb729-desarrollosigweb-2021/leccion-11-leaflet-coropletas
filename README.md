# Leaflet - mapas de coropletas
## leaflet-providers
El complemento [Leaflet Choropleth](https://github.com/timwis/leaflet-choropleth) simplifica la elaboración de un [mapa de coropletas](https://es.wikipedia.org/wiki/Mapa_coropl%C3%A9tico) en Leaflet.

Para utilizarse, primero debe descargarse el archivo [choropleth.js](https://raw.githubusercontent.com/timwis/leaflet-choropleth/gh-pages/dist/choropleth.js) e incluir un enlace a este en el código JavaScript, después del enlace a Leaflet. 

```html
<head>
  ...
  <script src="http://unpkg.com/leaflet@1.3.1/dist/leaflet.js"></script>
  <script src="js/choropleth.js"></script>
</head>
```

Puede ver un ejemplo de un mapa de coropletas en [https://tpb729-desarrollosigweb-2021.github.io/ejemplo-mapa-leaflet-coropletas/](https://tpb729-desarrollosigweb-2021.github.io/ejemplo-mapa-leaflet-coropletas/).

**Ejercicios**  
1. Agregue otra capa de coropletas al mapa del ejemplo (puede usar otra columna del mismo archivo de datos).
