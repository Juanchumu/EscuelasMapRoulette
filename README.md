# EscuelasMapRoulette


Este proyecto tiene como objetivo procesar y transformar el conjunto de datos geográficos del [Mapa Escolar](https://mapaescolar.abc.gob.ar/mapaescolar/), con el fin de integrarlos en el ecosistema de OpenStreetMap (OSM) mediante la plataforma MapRoulette.

El flujo de trabajo incluye la limpieza y estandarización del dataset original, el enriquecimiento de los registros con etiquetas (tags) compatibles con el esquema de OSM (como amenity=school, isced:level, operator:type, entre otros), y la generación de una capa geoespacial apta para su análisis y edición colaborativa.

Posteriormente, los datos son convertidos a un formato GeoJSON que puede ser cargado en MapRoulette, permitiendo a la comunidad validar, corregir y completar los datos directamente sobre el mapa, respetando las convenciones del modelado en OSM.

De esta manera, se busca mejorar la cobertura, precisión y semántica de la información educativa en OpenStreetMap, especialmente en zonas donde los datos están incompletos o desactualizados.


