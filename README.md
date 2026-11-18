# Junto a los archivos del proyecto se encuentra "Informe_tpe_especial.pdf" en el se detalla todo el trabajo que realizamos.
También proporcionamos el link al drive por si se prefiere abrirlo en google docs: 
https://docs.google.com/document/d/1NTf4-pDs0iY99hW5uYjsUHgvOkngz0HAAkhRwx0YJKg/edit?usp=sharing


# Flujo de trabajo:
### Para correr correctamente todos los archivos se recomienda:
1. Se recomienda comenzar leyendo el apartado 1 del informe, donde hablamos acerca del posible origen de los datos y que tipo de datos, incoherencias y faltantes que nos encontramos.

2. Crear un entorno virtual:
``` bash
sudo apt update
sudo apt install python3-venv
cd ruta-a-la-carpeta
python3 -m venv nombre-entorno
source nombre-entorno/bin/activate
```
3. Instalar los requerimientos:
``` bash
pip install -r requirements.txt
```

4. Ejecutar el archivo "Trabajo practico especial.ipynb en donde se encuentran todas las celdas del proyecto dandole a "run all"

5. Al ejecutar el archivo `Trabajo practico especial.ipynb` las celdas asociadas a la limpieza generarán un archivo llamado `dataset_limpio.parquet`. En el mismo cuaderno Jupyter se explican los pasos que se usaron y la justificación de cada uno.


6. Al ejecutar el archivo `Trabajo practico especial.ipynb`, en las celdas asocidadas a la seccion "analisis para las hipotesis" se intenta ver que posibles conclusiones podemos plantear a partir de los resutados obtenidos 

7. Para cada hiptesis en las distintas secciones de hipotesis que hay en el archivo  `Trabajo practico especial.ipynb`  se recomienda primero leer la documentación del informe correspondiente a cada una (definidas primero en el apartado 3 y desarrollas luego en el apartado 4 y 5 del informe), ya que aquí se indica como se va a abordar, y la justificación de cada elección.





