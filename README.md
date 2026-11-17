# En este enlace se encuentra el informe que realizamos:
[https://docs.google.com/document/d/1NTf4-pDs0iY99hW5uYjsUHgvOkngz0HAAkhRwx0YJKg/edit?usp=sharing]

# Flujo de trabajo:
### Para correr correctamente todos los archivos se recomienda:
1. Se recomienda comenzar leyendo el apartado 1 del informe, donde hablamos acerca del posible origen de los datos y que tipo de datos, incoherencias y faltantes que nos encontramos 

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

4. Ejecutar el archivo `limpieza.ipynb` que generará un archivo llamado `dataset_limpio.parquet`. En el mismo cuaderno Jupyter se explican los pasos que se usaron y la justificación de cada uno

5. Ejecutar `Analisis_para_hipotesis.ipynb`, donde exploramos el nuevo dataset con las técnicas vistas en clase, intentando ver que posibles conclusiones podemos plantear a partir del mismo 

6. Para cada `hipótesisX_nuestra.ipynb` se recomienda primero leer la documentación del informe correspondiente a cada una (definidas primero en el apartado 3 y desarrollas luego en el apartado 5 del informe), ya que aquí se indica como se va a abordar, y la justificación de cada elección. Posteriormente, se pueden ejecutar los cuadernos Jupyter donde se explica de forma menos detallada que es lo que se esta haciendo, en base al análisis previo realizado en el informe

7. Finalmente, hacer lo mismo que el paso anterior pero para con los cuadernos `hipotesis_catedra_X`, donde se abordan los apartados solicitados en el ejercicio 4


