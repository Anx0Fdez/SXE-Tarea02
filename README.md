# Tarea 02
### <u>*Actividad 1</u>:* 
*Descargar la imagen de Alpine Linux sin arrancarla.*
```bash
sudo docker pull alpine
```
*Comprobar que la imagen se ha descargado correctamente.*
```bash
sudo docker images
```
### <u>*Actividad 2</u>:* 
*Crea un contenedor sin ponerle nombre.* 
```bash 
sudo docker run -d alpine 
``` 
*Comprueba que el contenedor se ha creado.* 
```bash 
sudo docker ps -a 
``` 

### <u>*Actividad 3</u>:* 
*Crea un contenedor con el nombre "dam_alp1".* 
```bash
 sudo docker run -it -d --name dam_alp1 alpine 
```
*Para acceder al contenedor.*
```bash
sudo docker exec -it dam_alp1 /bin/sh
```




