## Práctica 1: Web Scraping

### Descripción

Este trabajo se ha realizado para asignatura Tipología y ciclo de vida
de los datos, del Máster en Ciencia de Datos de la Universitat Oberta 
de Catalunya. En ella, se aplican técnicas de *web scraping* mediante
el lenguaje de programación Python para extraer así datos de las webs
de la editorial Anagrama y de Amazon y generar un *dataset*.


### Miembros del equipo de trabajo

- Germán del Cacho Salvador

- Enrique Callejas Castro


### Código

Antes de la ejecución del código se recomienda la lectura del archivo 00_informe.pdf 
donde se explican las líneas generales del proyecto y se contextualiza el trabajo.

Se ejecutan en orden los siguientes *notebooks*.

- **01_scraper_anagrama.ipynb**: realiza el *scraping* de la página web de Anagrama y genera un .csv 
intermedio (*dataset.csv*) con los datos básicos de los libros (tiempo aproximado de ejecución: 50 minutos).

- **02_scraper_amazon.ipynb**: realiza el *scraping* de Amazon y fusiona los datos con el *dataset* 
anterior, creando el *dataset* final: *coleccion_anagrama.csv* (tiempo aproximado de ejecución: 10 horas).

- **03_analysis_coleccion_anagrama.ipynb**: analiza los datos del *dataset* final (tiempo aproximado de ejecución: 10 segundos).

Bonus:
Dado la gran cantidad de tiempo que requiere la ejecución de los *notebooks* anteriores, se ha desarrollado un
*notebook* extra: **04_scraper_lite**, que contiene las funciones de scraping de los notebooks 01_scraper_anagrama.ipynb y 
02_scraper_amazon.ipynb, pero que realiza el *scraping* sobre una cantidad limitada de libros, con el objetivo de que se pueda
ejecutar y probar en unos pocos segundos si se establece una *n* pequeña (e.g., n_books=3).

### Contacto

gdelcacho@uoc.edu

ecallejascastro@uoc.edu

