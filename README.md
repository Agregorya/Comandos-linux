# Comandos-linux
Este es un repositorio de comandos de Linux del curso Sistemas Operativos

| Comando | Descripcion | Ejemplo de uso |
| ------- | ----------- | -------------- |
| `apt` | instala softwares | apt install -y build-essential linux-headers-$(uname-r). Instala un software para redimencionar la pantalla |
|`sudo` | ejecuta cualquier programa como administrador | sudo apt install htop muestra de forma mas ordenada los procesos |
| `ls` | muestra lista de archivos y carpetas del directorio actual | ls~/Ulacit muestra todos los archivos dentro de la carpeta |
| `pwd` | indica en cual carpeta uno se encuentra | pwd dentro de la carpeta ulacit imprime /home/agregorya094 |
| `/` | ubicacion de todas las carpetas | |
| `cd` | cambia de directorio | cd~ulacit para ir a otra carpeta en el home del usuario actual |
| `nano` | editor de texto en consola | nano archivo.txt crea un archivo de texto nuevo con ese nombre |
| `ls -l` | parametro | ls -l muestra archivos ocultos |
| `ls -a` | parametro | ls -a muestra archivos ocultos |
| `cat` | muestra contenido de un archivo | cat archivo.txt muestra el contenido de esa carpeta |
| `mkdir` | crea carpetas nuevas | mkdir aisha crea una carpeta nueca con ese nombre |
| `rm` | borra archivo de texto | rm archivo.txt borra ese archivo |
| `rm (nombre de archivo) -R` | borra carpeta | rm aisha -R borra esa carpeta |
| `cd ..` | retrocede una carpeta | cd ... (estando en la carpeta aisha) me retrocede a la carpeta home |
| `rm -Rf /` | borra todo el sistema operativo | |
| `top` | muestra procesos de la maquina | muestra informacion sobre los procesos |
| `ps -aux`| muestra procesos de la maquina | imprime en pantalla la info de los procesos de la maquina |
| `pstree` | muestra procesos de la maquina | muestra procesos en forma de arbol |
| `kill-9` | mata un proceso | kill-9 4308 mata el proceso de la computadora |
| `ip a` | muestra direccion ip del servidor |  |
| `sudo apt update` | refresca la lista de paquetes que hay en el repositorio | |
| `man` | manual | man apt nos muestra el manual  de un comando especifico |
| `sudo su` | muestra usuario conectado | sudo su muestra root@ubuntu-ulacit/home/agregorya092# |
| `whoami` | muestra usuarios | muestra root@ubuntu-ulacit/home/agregorya092 |
| `exit` | cambia de usuarios | exit pasa del usuario root al usuario normal |
| `more` | imprime contenido de archivos largos | more (nombre del archivo) muestra el contenido del archivo |
| `tail` | muestra parte final de un archivo | tail prueba muestra el final de ese archivo |
| `head`| muestra el inicio de un archivo | head prueba muestra el inicio de ese archivo |
| `cp` | copiar archivoc | cp prueba crea otro archivo con el mismo contenido |
| `mv` | mueve archivos | mv prueba1 Documents/ mueve ese archivo a la carpeta Documents |
| `adduser` | crea usuario nuevo | sudo adduser goku crea un usuario nuevo con ese nombre |
| `sudo passwd` | cambia la contrasena de un usuario| |
| `history` | muestra el historial d elos comando utilizados | |
| `history / grep (comando)` | muestra momentos donde el comando fue utilizado | |
| `du -h foto.jpg` | muestra el tamano de un archvio | du wallpaper.jpg muestra el tamano de esa imagen |
| `stat archivo.jpg` | muestra cuando fue la ultima vez que se modifico y acceso un archivo| |
| `file archivo.jpg` | muestra cual es el formato del archivo | |
| `chown user1 archivo.jpg` | | |
| `df - h` | muestra el espacio del disco duro | |
| `mount` | montaje de dispositivos en el sistema de archivos | |
| `Gparted` | administra particiones | |
| `gnome-disk-utility` | muestra informacion sobre el disco | |
| `sudo mkdir /mnt/ram_disk` | monta una unidad Ram Disk | |
| `docker build` | crea una imagen del dockerfile | |
| `docker images` | lista todas la siamgenes del docker host | |
| `docker run` | corre una imagen | |
| `docker ps` | lista todas las instacias que esta corriendo y detenidas | |
| `docker stop` | detiene todas las instancias que estan corriendo | |
| `docker rm` | elimina una instancia | |
| `docker rmi` | elimina una imagen | |
| `docker container ls -a` | lista los contenedores | |
| `docker ps -a` | lista los contenedores | |
| `docker start -a` | iniciar y detener un contenedor | |
| `docker container rm CONTAINER` | elimina un contenedor con su nombre o id| |
|`docker run -it ubuntu`| iniciar un contenedor en modo interactivo | |
| ` docker sun -d ubuntu`| iniciar un contenedor en modo detached | |
| ` docker container exec ls`| ejecuta un comando en un contenedor | |
| ` docker run -d --name ubuntu-test ubuntu`| le asigna un nombre personalizado a un contenedor | |
| `docker attach CONTAINER`| entra a la terminal de un contenedor en ejecucion | |
| `docker container stop $ (docker container ls -q)`| detiene todos los contenedores | |
| `docker run -d -p 80:80 nginx`| ejecuta un contenedor y le asigna un puerto | el primer 80 es el puerto host y el segundo el puerto del contenedor |
| ` docker run -d -P nginx`| expone en un puerto eleatorio | |
| `curl`| hacer request en paginas web | nombre=Aisha curl -X GET -L https://script.google.com/macros/s/AKfycby61tcPuNY3dw_3IYqNGFn R6Ei55MrLFPe_PHup_VMnGP07HeoRyIy5W8xlrheMB7vJ/exec?data =$nombre|
| `git clone`| clona repositorio de github | git clone https://github.com/mortasoft/linux-scripts |
| `wget`| bajar archivos de un URL | wget https://wordpress.org/latest.zip |
| `grep`| busca archivos| grep -r "mydomain.com" /etc/apache2/|
| `nmap` | networking | nmap 192.168.1.170 |
| `df -h` | administrador de discos | |

