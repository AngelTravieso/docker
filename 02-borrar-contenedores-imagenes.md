# Borrar contenedores e imágenes:

## Contenedores

### Ver Contenedor:
ejecutandose: docker container ls
todos: docker container -a

### Detener un contenedor y eliminarlo:
docker container stop <container-id>
docker container rm <container-id>

Se puede borrar ya sea por nombre de contenedor o con los primeros 4 caracteres del hash del contenedor

### Eliminar todos los contenedores detenidos
docker container prune

## Imágenes

### Lista imagenes
docker image ls

### Eliminar imágen
docker image rm <image-id>
