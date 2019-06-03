# Diplodatos

### Análisis y Visualización
TP: AnalisisYVisualizacion/02_practico_I.ipynb

### Análisis y Curación
TP Limpieza: AnalisisYCuracion/notebooks/Limpieza.ipynb

TP Tablas: AnalisisYCuracion/notebooks/Ejercicio-tablas.ipynb

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
 
