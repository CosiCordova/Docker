# Docker
### git add README.md
### git commit -m "first commit"
### git push -u origin main

# Docker- Comandos Basicos
### **1- Descargar imagen ISO**
### *Docker pull ubuntu*
### **2- Crea un contenedor sin ponerle nombre. ¿está arrancado? Obtén el nombre**
### *El contenedor arranca correctamente bajo el nombre de stupefield_ellis*
### **3-  Crea un contenedor con el nombre 'ubu1'. ¿Como puedes acceder a él?**
### *Lo creo con el comando docker run -it --name ubu1 ubuntu y accedo a el con el comando docker star ubu1 bash para que este encendido y docker exec -it ubu1 bash para entrar en el*

### **4- Comprueba que ip tiene y si puedes hacer un ping a google.com**
### *Para comprobar la ip y hacer ping es necesario descargar los paquetes net-tools (herraminetas de internet) y iputils-ping (paquete para hacer ping). Posteriormente ejecutamos ping www.google.com*
### **5- Crea un contenedor con el nombre 'ubu2'. ¿Puedes hacer ping entre los contenedores?**
### *Se puede hacer perfectamente ping despues de instalar los paquetes correspondientes*
### **6- Sal del terminal, ¿que ocurrió con el contenedor?**
### *El contenedor sigue corriendo*
### **7- ¿Cuanta memoria en el disco duro ocupaste? ¿Hay alguna herramienta de docker para calcularlo?**
### *Utilize 77.8MB y se puede ver con docker ps --size*
### **8- ¿Cuanta RAM ocupan los contenedores? Crea cuantos contenedores necesites para calcularlo**

### *Para saber cuanta ram utilizan me sirve el comando docker stats (a mi me salio 2MB)*

