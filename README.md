# news-web-scraper
### La funcionalidad de estre proyecto consiste en: Extraer articulos periodisticos de dos diarios, ABC color conjunto a ultimahora, con ayuda de requests y beautifulsoup en python, los articulos son guardados en una computadora local, a su vez las imagenes de cada uno de los articulos tambien se ve guardada en una carpeta dentro del ordenador en el cual se ejecute el script de python.

Esos articulos pasan por un proceso de resumen a travez de una API de summarize, el resumen es almacenado en un txt al igual que el articulo. Los archivos pasan a ser unidos en un .docx, debido a la facilidad que conlleva colocar imagenes en el mismo. 

## Tecnologias y librerias utilizadas:

Todo el codigo de este proyecto se encuentra realizado en Python. Con ayuda de algunas librerias con las que cuenta dicho programa: Requests, bs4,lxml; las cuales son utilizadas para extraer datos valiosos desde la web, es decir, los articulos y las imagenes, aspose.words el cual convierte todos los archivos txt en un Word.

Y la principal herramienta que ayuda a el desarrollo del codigo fuente viene a ser la API de resumen de texto. La cual se optiene desde la pagina principal de la API, la cual nos provee un codigo de python el que recibe texto y lo resume, en este caso no recibe texto, sino un archivo de texto, el cual es guardado. La API tiene la posibilidad de realizar resumenes de 1 o 2 parrafos.

Para obtener mas informacion sobre la API, se puede leer la documentacion: [https://learn.meaningcloud.com/developer/summarization/1.0/doc](https://learn.meaningcloud.com/developer/summarization/1.0/doc)

## Estructura del Word:

- Imagen de la noticia.
- Titulo de la noticia.
- noticia completa.
- Link a la noticia.
- Resumen de la noticia.
