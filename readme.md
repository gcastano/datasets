 
# Datasets para practicar y aprender Ciencia de datos

Comparto datasets que voy consolidando que uso para ejemplos de código en el blog https://ellocodelosdatos.blogspot.com/ y que pueden ser útiles para quienes deseen aprender y practicar Python para Ciencia de datos.

Cada dataset es extraído de fuentes públicas y consolidado para que quede más fácil de de usar.




## Datasets disponibles

- [**gapminder_data.csv**](https://github.com/gcastano/datasets/blob/main/gapminder_data.csv) (26,878 registros 178 países)Archivo creado con varios datos consolidados de la página https://www.gapminder.org/data/ sobre datos demográficos por país, proyectados hasta el 2100

    | Campo | Tipo de datos |Descripción|
    | ------------- | ------------- |------------- |
    | continent | string | Continente |
    | country  | string |País|
    | year  | int |Año|
    | fertility  | float |Estimación de hijos por mujer en edad reproductiva|
    | lifeExpectancy  | float |Expectativa de vida al nacer
    | mean_house_income  | float | Ingreso promedio año en US$
    | median_age_year  | float |Mediana de la edad de la población
    | population  | float |Total de la población, redondeada a miles o millones

  Créditos FREE DATA FROM WORLD BANK VIA [GAPMINDER.ORG](https://www.gapminder.org/), CC-BY LICENSE [Read more](https://www.gapminder.org/free-material/)
- **Shows de TV extraidos de TVMaze.com** [TVMaze ofrece una completa API gratuita ](https://www.tvmaze.com/api) que pueden usar en sus proyectos, por ejemplo yo la uso en mi proyecto [TV Password Generator](https://tvpasswordgenerator.netlify.app/) y mediante un ciclo en Python extraje los datos y los procesé para tener datasets de diferentes tamaños, disponibles en CSV para que puedan usarlos directamente sin tener que descargarlos. Los datasets tienen los géneros de las series en un campo y también están ya codificados en columnas, lo que los hace útiles para diferentes modelos.
    - [TVMaze_Shows_Genres_encoded_1K.csv](https://github.com/gcastano/datasets/blob/main/TVMaze_Shows_Genres_encoded_1K.csv)
    - [TVMaze_Shows_Genres_encoded_10K.csv](https://github.com/gcastano/datasets/blob/main/TVMaze_Shows_Genres_encoded_10K.csv)
    - [TVMaze_Shows_Genres_encoded_25K.csv](https://github.com/gcastano/datasets/blob/main/TVMaze_Shows_Genres_encoded_25K.csv)
 
  Los campos son:
  
    |	Campo	|	Tipo de Datos	|	Descripción	|
    |	--------------	|	--------------	|	--------------	|
    |	id	|	int	|		|
    |	url	|	string	|		|
    |	name	|	string	|		|
    |	type	|	string	|		|
    |	language	|	string	|		|
    |	genres	|	string	|		|
    |	status	|	string	|		|
    |	runtime	|	float	|		|
    |	averageRuntime	|	float	|		|
    |	premiered	|	string	|		|
    |	ended	|	string	|		|
    |	officialSite	|	string	|		|
    |	rating	|	float	|	Calificación	|
    |	weight	|	int	|		|
    |	network	|	string	|		|
    |	network_name	|	string	|		|
    |	network_country	|	string	|		|
    |	network_country_code	|	string	|		|
    |	webChannel_name	|	string	|		|
    |	externals	|	string	|		|
    |	image	|	string	|		|
    |	summary	|	string	|		|
    |	Drama	|	float	|	Género	|
    |	Science-Fiction	|	float	|	Género	|
    |	Thriller	|	float	|	Género	|
    |	Action	|	float	|	Género	|
    |	Crime	|	float	|	Género	|
    |	Horror	|	float	|	Género	|
    |	Romance	|	float	|	Género	|
    |	Adventure	|	float	|	Género	|
    |	Espionage	|	float	|	Género	|
    |	Music	|	float	|	Género	|
    |	Mystery	|	float	|	Género	|
    |	Supernatural	|	float	|	Género	|
    |	Fantasy	|	float	|	Género	|
    |	Family	|	float	|	Género	|
    |	Anime	|	float	|	Género	|
    |	Comedy	|	float	|	Género	|
    |	History	|	float	|	Género	|
    |	Medical	|	float	|	Género	|
    |	Legal	|	float	|	Género	|
    |	Western	|	float	|	Género	|
    |	War	|	float	|	Género	|
    |	Sports	|	float	|	Género	|
    |	Food	|	float	|	Género	|
    |	Travel	|	float	|	Género	|
    |	Adult	|	float	|	Género	|
    |	Children	|	float	|	Género	|
    |	DIY	|	float	|	Género	|
    |	Nature	|	float	|	Género	|

## Cómo usarlos
Solo deben ir a cada dataset y tomar el código de su enlace raw y usarlo en sus códigos de Google Colab o Jupyter notebook directamente:

`dfDatos = pd.read_csv('https://raw.githubusercontent.com/gcastano/datasets/main/gapminder_data.csv')`

