# Ejercicio 1
Capacitación: Git, bash y docker

**Integrantes:**

- Joan Tasayco
- Angello Peña
- Carlos Gomez

**1. ¿Qué es y para qué sirve GIT?**

Git es una herramienta de control de versiones, que nos permite respaldar nuestro trabajo, compartirlo y controlar sus cambios.

**2. ¿Que es Github o bitbucket?**

Son repositorios remotos de codigo.

**3. ¿Qué es y para qué sirve el SSH?**

SH o Secure Shell, es un protocolo de administración remota que permite a los usuarios controlar y modificar sus servidores remotos a través de Internet. 

**4. ¿Que pasa si cambio de PC? ¿Tendré que generar el SSH nuevamente?¿Por qué?**

Si hay que generar un nuevo SSH, por que cada Key es unico por PC

**5. ¿Qué es markdown? ¿Para qué sirve?**

Markdown es un lenguaje de marcado que facilita la aplicación de formato a un texto empleando una serie de caracteres de una forma especial.  

**6. ¿Cómo inicializo y configuro un proyecto de git?**

Con el comando git init.

# Parte 5

## Listar las carpetas que hay dentro de la imagen

ejemplo: docker run -it --name Joan joan3/orbis-training-docker:0.2.0 ls -ls

## ¿Cuál es la diferencia entre docker ps y docker ps -a?

docker ps: lista los contenedores activos

docker ps -a: lista los contenedores activos e inactivos

## 1. ¿Cuál es la diferencia entre una imagen y un contenedor?

La imagen son un conjunto de archios que representa un aplicacion o conjuno de aplicaciones.

El conteneder es el espacio de memoria sobre el cual se ejecuta la imagene.

## 2. ¿Cómo listo las imágenes que hay en mi computadora?

Se lista con el sgte comando: docker images

## 3. ¿Cómo salgo de un contenedor de docker?

Con el siguiente comenado: exit

## 4. ¿Se elimina el contenedor al salir de ella?

Si esta creado de modo interactivo si elimina el contenedor.

## 5. ¿Cómo elimino un contenedor?

con el sgte comando: docker rm IDCONTENEDOR

## 6. ¿Para qué es necesario el flag `-i`, `-t`, `--rm`?

-i: ejecuta el contenedor de modo interactivo.

-t: actiua uso de la terminal tty.

--rm: automaticamente eliminara el contenedor cuando se salga

## 7. ¿Cómo verifico que el archivo creado se encuentra en la imagen?

ejecutando la imagen de un contenedor y listarlo.

docker run --name Mikhael -i angello/orbis-training-docker:0.2.0 ls /app

## 8. ¿Cómo se comenta una linea de código en Dockerfile?

Con el caracter #



