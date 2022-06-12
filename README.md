# Ejecutando-contenedores

## Santiago Guillen
***
- Ejemplo 1:
  Con el comando `docker pull ubuntu:18.04` descargaremos la imagen iso de ubuntu y con el comando `docker run -it ubuntu:18.04 /bin/bash` se crea el contenedor y         tendremos acceso a un shell en el   contenedor.
  ![](https://github.com/santygn/Ejecutando-contenedores/blob/2994284ecddf824cb6af7a80433cd714da6a7f50/img2/1.png)
  
- Ejemplo 2:  
  Con el comando `docker run ubuntu:18.04 ls` crearemos un contenedor de centOs:18.04 y muestra el contenido de la carpeta
  ![](https://github.com/santygn/Ejecutando-contenedores/blob/2994284ecddf824cb6af7a80433cd714da6a7f50/img2/2.png)
  
- Ejemplo 4:
  Con el comando `docker run -it -w /etc debian:9 ls` creamos un contenedor de debian y mostramos el contenido de la carpeta -w.
  ![](https://github.com/santygn/Ejecutando-contenedores/blob/2994284ecddf824cb6af7a80433cd714da6a7f50/img2/4.png)
