



# CSV
  
Módulo para el manejo de archivos CSV  
  
![banner](imgs/Banner_csv.png)
## Como instalar este módulo
  
__Descarga__ e __instala__ el contenido en la carpeta 'modules' en la ruta de rocketbot.  



## Descripción de los comandos

### Leer CSV
  
Lee un archivo CSV y guarda el contenido en una variable
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Ruta del archivo |Direccion del archivo que contiene los datos|C:/User/Usuario/Folder/file.csv|
|Separador|Caracter que separa los campos|,|
|Codificación|Codificación del archivo||
|Nombre de la varible donde se guardara el contenido|Nombre de la variable donde guardar resultado obtenido|Result|

### Exportar a CSV
  
Exporta datos a un archivo CSV
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Dato a exportar|Datos que seran exportados en un archivo CSV|[['data', 'data'], ['data', 'data']]|
|Delimitador|Delimitador de campos|,|
|Ruta del archivo|Ruta del archivo donde se guardarán los datos|C:/User/Usuario/Folder/file.csv|

### Exportar CSV a XLSX
  
Exporta archivo .csv a un archivo .xlsx
|Parámetros|Descripción|ejemplo|
| --- | --- | --- |
|Ruta del archivo CSV |Ruta donde se encuentra el archivo CSV|C:/User/Usuario/Folder/file.csv|
|Separador|Caracter separador|,|
|Codificación|Codificación del archivo||
|Guardar en |Ruta donde se guardará el archivo XLSX|C:/User/Usuario/Folder/file.xlsx|
