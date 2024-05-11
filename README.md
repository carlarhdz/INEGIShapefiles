# INEGI Shapefiles
Repo de la clase de INEGI Shapefiles (2024)

![Equipo INEGI](Equipo.jpeg)

## Instrucciones para la clase

### 1. Prepararar el repositorio

**a) Fork del repositorio**: Realicen un fork del repositorio de la clase en GitHub.

**b) Clonar el repositorio**: Clonen el fork del repositorio a su máquina local.

**c) Descomprimir los archivos**: Encontrarán dos folders en el repositorio llamados Escuelas y Estados. Dentro de cada uno, corran el siguiente comando:
```bash
unzip conjunto_de_datos.zip 
```

### 2. Abrir el Jupyter Notebook

**a) Construir el docker**: Primero vamos a constuir nuestra imagen
```bash
docker build -t inegi . 
```

**b) Correr el docker**: Ahora sí podemos correr el Docker con
```bash
docker build -t inegi .
```

**c) Entrar al notebook**: Copien el link http://127.0.0.1:8888/lab en su browser


## Instrucciones para la tarea

### 1. Crear una copia de la tarea

**a) Crear branch**: Hagan una nueva branch para trabajar en tus tareas.

**b) Hacer su carepeta**: Dentro de la carpeta de tareas, crear una subcarpeta con su matrícula

**c) Crear una copia de la tarea**: Ahora pueden copiar el archivo de la tarea a su propia carpeta

### 2. Subir la tarea

**a) Modificar su archivo**: Sigan todas las instrucciones en el archivo de la tarea 

**b) Merge**: Una vez que terminen hagan merge a su main

**c) Pull request**: Realicen un pull request de su carpeta al repositorio original