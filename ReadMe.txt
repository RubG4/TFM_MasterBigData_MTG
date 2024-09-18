Preparacion.

    1 - Descargar los datos de Kaggle en el siguiente link https://www.kaggle.com/datasets/mylesoneill/magic-the-gathering-cards/discussion?sort=undefined
            Necesarios la carpeta "AllDecksFiles" y el archivo "AllCards.JSON"
    
    2 - Colocar los descargados de Kaggle en la ruta "../Datos/AllCards.json" (archivo json de las cartas) y "..\Datos\AllDeckFiles" (fichero que contiene los JSON de los mazos)
    
    3 - Necesario disponer de mongoDB en local.

Ejecución

    1 - Lanzar "MongoBD.ipynb" para crear las colecciones en MongoDB.
    
    2 - En caso de primera ejecución lanzar los ficheros "Analisis*.ipynb" necesario para ser llamados por el resto de archivos.
    
    3 - Ejecutar "Main.ipynb", llamara a los ficheros Analisis y realizara el tratamiento de datos.
    
    4 - Ejecutar los modelos supervisados y no supervisados para probar los modelos.