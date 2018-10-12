#Construir una imagen
docker build -t joan3/orbis-training-docker:0.1.0 .
#Subir una imagen al DockerHub
docker push joan3/orbis-training-docker:0.1.0
#Cambiar de version con tag
docker tag joan3/orbis-training-docker:0.1.0 0.2.0
#Construir la imagen 0.2.0
docker build -t joan3/orbis-training-docker:0.2.0 .
#Subir una imagen 0.2.0 al DockerHub
docker push joan3/orbis-training-docker:0.2.0

#Preguntas

1. ¿Qué importancia tiene los tags en un proyecto?

Los tags en un proyecto son importantes ya que permite tener versionado el proyecto.

2. ¿Cuál es la diferencia entre un tag normal y un tag anotado en git?

tag normal: me permite versionar el proyecto pero sin ningun comentario.
tag anotado en git: me permite agregar un comentario al versionado, la cual da mayor claridad algun cambio y/o creación de un archivo

3. ¿Cómo se sube todos los tags de git que hay en mi local?

Utilizando el comando: git push origin --tags

4. ¿Es necesario loguearse cada vez que subo una imagen a dockerhub?

Solo es necesario loguearse una vez en la cuenta dockerhub

5. ¿Qué es y para qué sirve docker?

Es una plataforma Open Source que brinda un estándar para desarrollar, implementar y ejecutar aplicaciones dentro de contenedores.

6. ¿Cuál es la diferencia entre docker y VirtualBox (virtualización)?

Docker: comparte recursos del hardware y lo distribuye.
VirtualBox: es un sistema operativo completo funcionando de manera aislada sobre otro sistema operativo completo. 

7. ¿Es necesario depender de una imagen de docker base al crear una imagen nueva?


8. ¿Porqué debo anteponer el nombre de usuario en una imagen docker nueva?


9. ¿Que pasa si creo una imagen sin especificar una versión o tag, con qué versión se crea?
