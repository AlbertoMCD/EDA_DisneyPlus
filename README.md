# EDA_DisneyPlus
Repositorio para proyecto EDA sobre contenido de la plataforma Disney+

Disney+ es una de las plataformas de streaming más populares, tiene alrededor de 1300 películas o series de televisión disponibles; a mediados de 2021, tenían alrededor de 116 millones de suscriptores mundialmente. 

![](https://media.giphy.com/media/T9KcDBkWHrWJLF2l5Q/giphy.gif)

Fuente: [Giphy](https://media.giphy.com/media/T9KcDBkWHrWJLF2l5Q/giphy.gif)

En este proyecto se emplea el dataset [Disney+ Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/disney-movies-and-tv-shows), consiste en el listado de todas las películas y series disponibles en la plataforma, junto con detalles como los que se listan a continuación:

#### Campos:

- <b> show_id:</b> id único por película
- <b> type:</b> película o serie
- <b> title:</b> nombre de la película/serie
- <b> director:</b> directores
- <b> cast:</b> reparto principal
- <b> country:</b> país (países) de producción
- <b> date_added:</b> fecha de liberación/adición en Disney+
- <b> release_year:</b> año de publicación/estreno original
- <b> rating:</b> clasificación
- <b> duration:</b> duración total
- <b> listed in:</b> género(s)
- <b> description:</b> descripción del material

## Resultados

El notebook empleado para la obtención de resultados se encuentra [aquí](https://github.com/AlbertoMCD/EDA_DisneyPlus/blob/main/src/EDA_DisneyPlus.ipynb).

- En la base de datos hay 1052 películas y 398 series de televisión.
- El rango de fechas de adición de películas/series va desde 01/10/2019 hasta 26/11/2021.
- El rango de fechas de estreno de películas/series va desde 1928 hasta 2021.
- Las clasificaciones de las películas/series:
    * TV-G
    * PG
    * TV-PG
    * PG-13
    * TV-14
    * G
    * TV-Y7
    * TV-Y
    * TV-Y7-FV
- Hay 45 géneros distintos, entre los cuales se encuentran: 
    * Anime
    * Series
    * Family
    * Sports
    * Documentary
    * Romance
    * Disaster
    * Crime
    * Fantasy
    * Historical
- Existen 49 países distintos de producción, entre los cuales se encuentran: 
    * Denmark
    * Sweden
    * Iran
    * Mexico
    * United Arab Emirates
    * Poland
    * Austria
    * Ireland
    * South Korea
    * Belgium

![](https://github.com/AlbertoMCD/EDA_DisneyPlus/blob/main/results/generos_1.png)
![](https://github.com/AlbertoMCD/EDA_DisneyPlus/blob/main/results/pais_2.png)
![](https://github.com/AlbertoMCD/EDA_DisneyPlus/blob/main/results/clasificacion.png)
![](https://github.com/AlbertoMCD/EDA_DisneyPlus/blob/main/results/titulo.png)
![](https://github.com/AlbertoMCD/EDA_DisneyPlus/blob/main/results/descripcion.png)

