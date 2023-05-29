# Proyecto de Física Computacional 2 - 2023_1
## Edward García Hernández & Daniel Esteban Salazar Camacho

En este repositorio está el notebook del proyecto final del curso de Física Computacional 2. En esta ocasión se utilizaron 10 especies de la base de datos BirdClef 2023
para clasificarlos con base en sus audios. Cada especie contiene alrededor de 90 audios en formato ```.ogg```.

La red convolucional que se usa consta de 5 bloques residuales con capas de convolución entre medias (2 ch --> 8 ch --> 16 ch --> 32 ch --> 64 ch --> 128 ch). Además,
al final de la red cuenta con un clasificador lineal simple. Debe notarse que esto no es una entrada al concurso BirdClef2023 pues no cumple con la estructura de red
exigida por el torneo; se consideró que, por los usos de las CNN, una clasificación por espectrogramas sería la adecuada.

Resultados:

$Validation Accuracy = 0.73$
