### 2012_split_A_b.ipynb

* Este código concatena dos archivos de texto que contienen rutas a imágenes
* Busca los nombres de las imágenes
* Con el nombre, busca el archivo label.txt correspondiente a cada imágen
* Si el archivo contiene uno de los tres labels (bird, cow o sheep) crea un archivo label, y almacena la ruta de la imágen en archivo B.txt, ignorando cualquiera de los otros 17 labels
* Si el archivo contiene otro label, crea el archivo label, y almacena la ruta de la imágen en archivo A.txt