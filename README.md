# Instrucciones para Ejecutar el Proyecto 

## Requisitos Previos

### Programas Necesarios

Asegúrate de tener instalados los siguientes elementos antes de proceder:

1. [Docker Desktop](https://www.docker.com/products/docker-desktop): Si aún no lo tienes instalado, descárgalo e instálalo en tu sistema operativo.

2. [Git Bash](https://gitforwindows.org/): Si no lo tienes instalado, asegúrate de que Git Bash esté disponible en tu sistema.

### Repositorios Necesarios

1. [BackEnd](https://github.com/Sanvalencia0343/BackNewInnTech.git): Contiene la logica de progrmación, junto con la conexion a la Api.

2. [FrontEnd](https://github.com/Sanvalencia0343/FrontNewInnTech.git): Contiene la parte visual del proyecto.

3. [Docker-Compose](https://github.com/Sanvalencia0343/DockerNewInnTech.git): Contiene la configuración del entorno para desplegar el proyecto.

## Estructura Encarpetado

1. Crear una carpeta padre que contendrá los 3 respositorios anteriormente mencionado. 

2. Abrir Git Bash y navegar hasta la carpeta padre usando el comando "cd nombre-carpeta". "cd Documentos"

3. Mediante el comando "git clone link-repositorio" se extrae los archivos almacenados en el repositorio. Se debe hacer lo mismo con los 3 repositorios.
Nota: Al clonar el respositorio Docker-Compose , se debe de mover el archivo "docker-compose.yml" a la raiz de la carpeta padre. Se sugiere la carpeta padre tenga esta estructura

carpeta-padre/
|-- back/
|   |-- ...  # Archivos y carpetas relacionados con el backend
|
|-- front/
|   |-- ...  # Archivos y carpetas relacionados con el frontend
|
|-- docker-compose.yml  # Archivo de configuración Docker Compose


## Pasos para Ejecutar el Proyecto

1. Abre la terminal Git Bash en la carpeta padre del proyecto. Puedes hacerlo siguiendo estos pasos:

   - Navega a la carpeta padre utilizando el Explorador de Windows.
   - Haz clic derecho en un espacio vacío dentro de la carpeta.
   - Selecciona la opción "Git Bash Here" en el menú. Esto abrirá una terminal Git Bash en la ubicación de la carpeta.

2. Una vez que tienes la terminal Git Bash abierta, ejecuta el siguiente comando para iniciar el proyecto con la ayuda de contenedores Docker:

   docker-compose up -d

3. Esto iniciará los contenedores Docker. Los contenedores para el backend y el frontend se ejecutarán y se vincularán automáticamente.

4. Se abrira una ventana nueva en el navegador con el proyecto desplagado.
