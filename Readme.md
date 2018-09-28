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
