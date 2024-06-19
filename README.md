# Documentacion-desarrollo-docker

Repositorio para practicar buenas practicas de desarrollo -> https://12factor.net/es/

## Docker

Es una tecnologia que lo que nos permite es armar , administrar , empaquetar y deployar aplicaciones de forma mas sencilla porque se utiliza el concepto de CONTENEDOR.
UN CONTENEDOR ES DONDE TENEMOS TODAS NUESTRAS CONFIGURACIONES NECESARIAS PARA QUE NUESTRA APLICACION FUNCIONE SIN PROBLEMAS EN CUALQUIER LUGAR DONDE SE EJECUTE.

* Facilita la gestion de ambientes.
* Facilita el deploy
* Se utiliza en MICROSERVICIOS.
* son distintas a las maquinas virtuales porque las mv emulan una maquina fisica en el se instala el so mientras que los contenedores usan el kernel del so

El trabajo con docker consiste en 3 etapas:

![image](https://github.com/maximilianofni/Documentacion-devs-docker/assets/17895688/0398a4c8-72d3-481c-b128-2e9e4cbaf2e1)

* Dockerfile ees un archivo que contiene todos los comandos e instrucciones para instalar todas las dependencias de una aplicacion
* A partir del dockerfile se crea la imagen de docker que es un ejecutable que ya contiene todas las dependencias y el software a correr
* A apartir de ese iamgen se puede crear los contenedores, es decir el contenedor es la iamgen ya funcionando ya corriendo y uno ya puede programar directamente en ese contenedor.

Nota: Se puede llevar el registro de versiones utilizando GIT (oara saber la version correcta del contenedor)

SI LO VEMOS COMO POO LA IMAGEN ES LA CLASE Y LOS CONTENEDORES SON LOS OBJETOS. 



