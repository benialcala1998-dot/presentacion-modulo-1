# Propuesta del proyecto

Rellenadla y enseñádmela antes de empezar el EDA. Son diez minutos que os pueden ahorrar días.

Nombre: Benito

## 1. La idea

Título del proyecto:
Participación electoral y resultados por tamaño de municipio
¿Qué pregunta responde y a quién le interesa?
Interesa a cualquier persona que quiera comparar resultados electorales municipales. Responde a cómo varían la abstención y los porcentajes de voto según el tamaño de población del municipio.
## 2. Los datos

De dónde salen:
- [x] Kaggle
- [ ] Hugging Face
- [ ] Datos míos (dónde los he encontrado)

Enlace a los datos: https://www.kaggle.com/datasets/mlprojectbth/spanish-region-and-election-results
Licencia: Kaggle muestra “Unknown”; hay que comprobar con el autor si se permite redistribuir el CSV antes de subir los datos al repositorio público.

Cuántas filas y columnas tienen: el archivo cargado tiene 8.119 filas y 52 columnas; el CSV preparado para la app tiene 8.119 filas y 13 columnas (12 seleccionadas y el grupo de tamaño municipal). La ficha indica que faltan algunas regiones porque las fuentes estaban incompletas.

Qué es cada fila (un vino, un partido, una venta...):
 Una de las regiones/municipios incluidos en el conjunto. La ficha describe la población a 1 de enero de 2015, pero no identifica claramente el año de los resultados electorales.
Comprobado (los requisitos están en 03_DATOS.md):
- [x] Son tabulares, en una sola tabla
- [x] No los hemos usado en clase
- [x] Tienen más de 1.000 filas
- [x] Tienen al menos 6 columnas, con números y con texto
- [x] Entiendo qué es cada columna
- [x] Hay algo que limpiar
- [x] He confirmado el enlace público
- [x] He confirmado que la licencia permite publicar los datos
- [x] El CSV limpio pesará menos de 100 MB

## 3. Tres preguntas que quiero responder

1. ¿Cómo cambia la abstención media entre municipios pequeños, medianos y grandes?
2. ¿Cómo varían los porcentajes medios de voto al PP y al PSOE según el tamaño del municipio?
3. ¿Cambian los porcentajes de votos en blanco y nulos entre municipios con abstención por debajo o por encima de la mediana?

## 4. La app

¿Qué filtros pondrías en la barra de la izquierda?
 - Tipo de municipio por tamaño
- Rango de población
- Selección de municipio
¿Qué pregunta le harías al usuario al final? (como "¿Cuánto cobrarías por tu piso?")
 Selecciona tu municipio: ¿crees que la participación en tu pueblo/ciudad fue mayor o menor que la media nacional?
¿Tienen coordenadas para hacer un mapa?
- [ ] Sí
- [x] No. Se utilizarán gráficos de barras, histogramas y diagramas de dispersión; el conjunto no incluye provincia ni Comunidad Autónoma.

## 5. Plan B

Por si los datos principales no sirven, otros distintos:
 Dataset de resultados de partidos de fútbol entre selecciones internacionales (1872 - Presente) en Kaggle.
Enlace:
https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017