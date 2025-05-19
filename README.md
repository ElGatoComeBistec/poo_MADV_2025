# poo_MADV_2025
ejercicios de poo con python :v

## 1. Ejemplos de Poo

````shell
*.pyc
__pycache__/
.venv/
````

 ## 3. Se crea el ambiente virtual de trabajo de python

 ````shell
 python3 -m venv .venv
 ````

 ## 4. Iniciar el **virtual Enviroment**

 Se activa el **Virtual enviroment** para instalar las librerias necesarias para el proyecto

 ````shell
 source .venv/bin/activate
 ````

 Se actualiza la vercin instalada de **pip** para poder descargar las ultimas verciones de las librerias

 ````shell
 pip install --upgrate pip 
 ````

 ## 5. Verifica las librerias y verciones instaladas

 se verifica que librerias y verciones se tienen instaladas

 ````shell
 pip freeze
 ````

 ## 6. Instalar las librerias que van a ocupar el proyecto.

 ````shell
 pip install web.py
 ````

 ## 7. Creear el archivo **requirements.txt** con las librerias y el numero de verciones utilizadas

 ````shell
 pip freeze > requirements.txt
 ````

 ## 8. Creear el archivo **rutime.txt**

python3 -V > runtime.txt

 ## 9. Indexar los archivos y cambios realizados en el proyecto

 ````shell
 git add.
 ````

 ## 10. Generear un **commint**con un texto que describa los cambios realizados en el proyecto

 ````shell
 git commint -m "CREATED configuracion basica"
 ````

 ## 11. Realizar un **push**

 se realiza un **push** para subir los cambios realizados al repocitorio de **GitHub**

 git push -u origin main
 
