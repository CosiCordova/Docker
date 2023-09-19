# Docker
### git add README.md
### git commit -m "first commit"
### git push -u origin main

# Docker- Comandos Basicos
### 1- Descargar imagen ISO
### 2- Crea un contenedor sin ponerle nombre. ¿está arrancado? Obtén el nombre
### El contenedor arranca correctamente bajo el nombre de stupefield_ellis
### 3-  Crea un contenedor con el nombre 'ubu1'. ¿Como puedes acceder a él?
### Lo creo con el comando docker run -it --name ubu1 ubuntu y accedo a el con el comando docker start ubu1

### 4- Comprueba que ip tiene y si puedes hacer un ping a google.com
### Para comprobar la ip y hacer ping es necesario descargar los paquetes net-tools (herraminetas de internet) y iputils-ping (paquete para hacer ping) colocando ping www.google.com
### 5- Crea un contenedor con el nombre 'ubu2'. ¿Puedes hacer ping entre los contenedores?
### Se puede hacer perfectamente ping
### Sal del terminal, ¿que ocurrió con el contenedor?
### El contenedor sigue funcionando

