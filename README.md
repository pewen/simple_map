# simple_map
Herramienta que crea un mapa html (con folium/leaflet) desde un csv

## instalacion

`pip install -r requeriments.txt`

## uso

``` python
usage: simple_map.py [-h] --lat LAT --log LOG --zoom ZOOM --input INPUT --out
                     OUT

Crea un mapa html (usando folium/leaflet) usando el csv de entrada. El csv
debe tener las columnas: lat, log y title

optional arguments:
  -h, --help     show this help message and exit
  --lat LAT      latitud inicial
  --log LOG      longitud inicial
  --zoom ZOOM    nivel de zoom inicial
  --input INPUT  path al csv de entrada
  --out OUT      path/nombre de la salida
```

## example

`python simple_map.py --lat -33 --log -64.4 --zoom 10 --in sample.csv --out example.html`
