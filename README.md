# __Repositorio__

#### TFG realizado por Ramón Costa González

___

En este repositorio se incluye el dataset utilizado para realizar el entrenamiento y las pruebas del modelo desarrollado, además de las instrucciones para poder utilizar el código realizado en el cuaderno.

### Instrucciones

Haciendo click en este [enlace](https://colab.research.google.com/drive/1hJe84-nBWKQTNFczvNkmO2gEXduhtOpu) se puede acceder al cuaderno de colab en el que se ha implementado el sistema. Para poder ejecutar las celdas de código y realizar cambios las instrucciones a seguir son las siguientes (Es necesario poseer una cuenta de Google):

1. Hacer click en el enlace mencionado arriba e iniciar sesión con la cuenta de Google.

2. Una vez abierto el cuaderno de Colaboratory, se debe guardar una copia de este cuaderno en su propia cuenta de Drive haciendo click en "Archivo-> Guardar una copia en Drive..."

3. En el propio cuaderno ejecutar la primera celda de código para que se inicie la conexión con la GPU de Google. A continuación, ejecutar la siguiente celda de código para dar los permisos necesarios a la API de Google Drive para acceder a los datos.

4. En la ventana de resultados de código se generará un enlace que se debe abrir y seguir las instrucciones que se indican. Se generará un código que se debe introducir y pulsar intro para continuar.

5. Cargar los datos del dataset y el modelo entrenado en la cuenta de Google Drive.

6. Seleccionar el archivo de datos que se desea cargar en el cuaderno y pulsar el botón "compartir". Se copiará el enlace en el portapapeles automáticamente. Introducir los datos de la carpeta 'Complete' para cada grupo de personas. 

7. Copiar el 'id' de cada archivo en  las lineas de código pertenecientes a cada archivo (Seguir las instrucciones que se incluyen en el propio cuaderno). Cuando se hayan copiado todos los 'id' de los archivos se podrá ejecutar la celda de código.

### Estructura del Dataset

En primer lugar, agradecer a Marzia Pipino la cesión de los datos para su utilización en este trabajo. Para ver el repositorio con el dataset completo de Marzia se debe seguir el siguiente enlace, [Marzia Dataset](https://github.com/Marpino/Walking-dataset). 

En la carpeta 'RamonDataset', podemos encontrar en su interior dos carpetas, 'Elderly' y 'Young'. En cada una de se encuentran los datos ya calibrados, en dos carpetas, los archivos que corresponden solo a los valores de aceleración y los que se encuentran los valores de aceleración linear y velocidad angular de todos los sensores.
