# Propuesta del proyecto

Rellenadla y enseñádmela antes de empezar el EDA. Son diez minutos que os pueden ahorrar días.

Nombre: Benito

## 1. La idea

Título del proyecto:
Radiografía Electoral de España: Análisis de la Participación y Tendencias de Voto por Municipios (Elecciones Generales 2023)
¿Qué pregunta responde y a quién le interesa?
(por ejemplo: "A un restaurante le interesa saber qué vinos tienen buena nota sin ser caros, para su carta")
Interesa a analistas políticos, periodistas, consultores de comunicación y partidos. Responde a cómo varía la abstención entre el ámbito rural y el urbano, qué regiones muestran mayor fragmentación política y cuáles son las fortalezas de cada bloque según la población.
## 2. Los datos

De dónde salen:
- [ ] Kaggle
- [ ] Hugging Face
- [X] Datos míos (dónde los he encontrado): Portal Infoelectoral del Ministerio del Interior de España (Ministerio del Interior)

Enlace a los datos: https://www.infoelectoral.interior.gob.es/infoelectoral/doc/datos_elecciones_202307_generales_municipios.zip

Cuántas filas y columnas tienen: Más de 8.100 filas (una por cada municipio de España) y unas 15 columnas con datos de censo, participación, votos en blanco, nulos y resultados por formación política

Qué es cada fila (un vino, un partido, una venta...):
 Un municipio español en las Elecciones Generales del 23 de julio de 2023
Comprobado (los requisitos están en 03_DATOS.md):
- [x] Son tabulares, en una sola tabla
- [x] No los hemos usado en clase
- [x] Tienen más de 1.000 filas
- [x] Tienen al menos 6 columnas, con números y con texto
- [x] Entiendo qué es cada columna
- [x] Hay algo que limpiar
- [x] Sé de dónde salen y se pueden usar
- [x] El CSV limpio pesará menos de 100 MB

## 3. Tres preguntas que quiero responder

1. ¿Hay diferencias significativas en la tasa de abstención entre municipios pequeños (ámbito rural) y grandes capitales de provincia?
2. ¿Qué provincias o Comunidades Autónomas presentan la mayor fragmentación de voto entre bloques políticos?
3. ¿Cómo se distribuye el porcentaje de voto en blanco y nulo en función del tamaño del censo municipal?

## 4. La app

¿Qué filtros pondrías en la barra de la izquierda?
 - Comunidad Autónoma
- Provincia
- Rango de población / censo del municipio
¿Qué pregunta le harías al usuario al final? (como "¿Cuánto cobrarías por tu piso?")
 Selecciona tu municipio: ¿crees que la participación en tu pueblo/ciudad fue mayor o menor que la media nacional?
¿Tienen coordenadas para hacer un mapa?
- [ ] Sí
- [x] No. Se utilizarán gráficos de barras, diagramas de dispersión y comparativas por provincia/comunidad

## 5. Plan B

Por si los datos principales no sirven, otros distintos:
 Dataset de resultados de partidos de fútbol entre selecciones internacionales (1872 - Presente) en Kaggle.
Enlace:
https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017