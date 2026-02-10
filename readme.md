# Requisitos
El notebook esta optimizado para funcionar en una GPU con NVIDIA CUDA

Ejecutar con un entorno de anaconda con python 3.10, escribir el siguiente comando para crear el entorno virtual de conda
conda env create -f condaEnvironment.yml

descargar resistant.zip, suceptible.zip y extraer en la misma carpeta del proyecto con el mismo nombre. (no estan en el repositorio descomprimidos porque pesan demasiado, 30gb aproximadamente)

Dataset:
https://drive.google.com/file/d/1xMlt-UtKFOpijfkyq46fme7TU-QuYhxF/view?usp=drive_link
https://drive.google.com/file/d/105Q93hSWU8Fb877-monMQq3BKAk1aUfy/view?usp=drive_link

Si desea ejecutar sin estos dos datasets puede hacerlo cargando los datos procesados del archivo kmers.csv, para esto ejecute la primera celda para cargar las librerias y ejecute las celdas a partir de 3. Visualizar datos
