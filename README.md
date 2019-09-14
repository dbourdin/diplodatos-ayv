# Diplodatos

### Análisis y Visualización
TP: AnalisisYVisualizacion/02_practico_I.ipynb

### Análisis y Curación
TP Limpieza: AnalisisYCuracion/notebooks/Limpieza.ipynb

TP Tablas: AnalisisYCuracion/notebooks/Ejercicio-tablas.ipynb

### Aprendizaje No Supervisado
Para poder correr el trabajo práctico, es necesario descargar el dataset de movielens:
http://files.grouplens.org/datasets/movielens/ml-20m.zip
Una vez descargado, ubicar los archivos ratings.csv y movies.csv dentro de la carpeta AprendizajeNoSupervisado/ml-20m/

TP: AprendizajeNoSupervisado/TP_Reglas_de_asociacion.ipynb

##
### Pasos para correr las notebooks (Ubuntu)

* Instalar Anaconda:
```
$ wget https://repo.anaconda.com/archive/Anaconda3-2018.12-Linux-x86_64.sh
$ bash Anaconda3-2018.12-Linux-x86_64.sh
$ source ~/.bashrc
```

* Crear un environment con Anaconda:
```
$ conda create --name diplodatos python=3.6 anaconda
```

* Activar el environment creado:
```
$ source activate diplodatos
```

* Instalar requerimientos del proyecto:
```
$ conda install --file requirements.txt
```

* Correr jupyter notebook:
```
$ jupyter notebook
```

* Correr la notebook desde el browser. Ej AnalisisYCuracion/notebooks/Ejercicio-tablas.ipynb para el ejercicio de tablas de Análisis y Curación
 
