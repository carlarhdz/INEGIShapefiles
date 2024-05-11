# INEGI Shapefiles
Repo de la clase de INEGI Shapefiles (2024)

Pueden seguir la presentación en la siguiente liga: https://docs.google.com/presentation/d/1j9SAmgaysk03lOlU6FAR02WHmzZbecQLZXAUfpXVQyQ/edit?usp=sharing

![Equipo INEGI](Equipo.jpeg)

## Instrucciones para la clase

### 1. Prepararar el repositorio

**a) Fork del repositorio**: Hagan un fork del repositorio de la clase.

**b) Clonar el repositorio**: Clonen el fork del repositorio a su máquina local.

**c) Descargar los archivos**: Descargar los dos folders que encontrarán en el siguiente Drive: https://drive.google.com/drive/folders/148x930R0csfe-GIkDxwEYyj0ALbd_wfH?usp=sharing

**d) Mover al repositorio**: Los folders se descargarán como zips. Mover ambos al repositorio y descomprimirlos.


### 2. Abrir el Jupyter Notebook

**a) Construir el docker**: Primero vamos a constuir nuestra imagen
```bash
docker build -t inegi . 
```

**b) Correr el docker**: Ahora sí podemos correr el Docker con
```
docker run -p 8888:8888 inegi
```

**c) Entrar al notebook**: Copien el link http://127.0.0.1:8888/lab en su browser


## Instrucciones para la tarea

### 1. Preparar su carpeta

**a) Crear su propia carpeta**: Dentro de la carpeta de tareas, crear una subcarpeta con su matrícula y sus iniciales

**b) Crear una copia**: Ahora pueden copiar el archivo de la tarea a su propia carpeta

**c) Descargar los nuevos datos**: Tendrán que descargar el shapefile 'servicios profesionales, científicos y técnicos'. Muévanlo para que esté dentro de su carpeta de tareas.

### 2. Subir la tarea

**a) Modificar su archivo**: Sigan las instrucciones en el archivo de la tarea 

**b) Adds y commits**: ¡Recuerden solo subir cambios de archivos dentro de su propia carpeta!

**c) Pull request**: Realicen un pull request al repositorio original.
