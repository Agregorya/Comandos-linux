# Comandos-linux
Este es un repositorio de comandos de Linux del curso Sistemas Operativos

| Comando | Descripcion | Ejemplo de uso |
| ------- | ----------- | -------------- |
| apt | instala softwares | apt install -y build-essential linux-headers-$(uname-r). Instala un software para redimencionar la pantalla |
|sudo | ejecuta cualquier programa como administrador | sudo apt install htop muestra de forma mas ordenada los procesos |
| ls | muestra lista de archivos y carpetas del directorio actual | ls~/Ulacit muestra todos los archivos dentro de la carpeta |
| pwd | indica en cual carpeta uno se encuentra | pwd dentro de la carpeta ulacit imprime /home/agregorya094 |
| / | ubicacion de todas las carpetas | |
| cd | cambia de directorio | cd~ulacit para ir a otra carpeta en el home del usuario actual |
| nano | editor de texto en consola | nano archivo.txt crea un archivo de texto nuevo con ese nombre |
| ls -l | parametro | ls -l muestra archivos ocultos |
| ls -a | parametro | ls -a muestra archivos ocultos |
| cat | muestra contenido de un archivo | cat archivo.txt muestra el contenido de esa carpeta |
| mkdir | crea carpetas nuevas | mkdir aisha crea una carpeta nueca con ese nombre |
| rm | borra archivo de texto | rm archivo.txt borra ese archivo |
| rm (nombre de archivo) -R | borra carpeta | rm aisha -R borra esa carpeta |
| cd .. | retrocede una carpeta | cd ... (estando en la carpeta aisha) me retrocede a la carpeta home |
| rm -Rf / | borra todo el sistema operativo | |
| top | muestra procesos de la maquina | muestra informacion sobre los procesos |
| ps -aux| muestra procesos de la maquina | imprime en pantalla la info de los procesos de la maquina |
| pstree | muestra procesos de la maquina | muestra procesos en forma de arbol |
| kill-9 | mata un proceso | kill-9 4308 mata el proceso de la computadora |
| ip a | muestra direccion ip del servidor |  |
| sudo apt update | refresca la lista de paquetes que hay en el repositorio | |
| man | manual | man apt nos muestra el manual  de un comando especifico |
| sudo su | muestra usuario conectado | sudo su muestra root@ubuntu-ulacit/home/agregorya092# |
| whoami | muestra usuarios | muestra root@ubuntu-ulacit/home/agregorya092 |
| exit | cambia de usuarios | exit pasa del usuario root al usuario normal |
| more | imprime contenido de archivos largos | more (nombre del archivo) muestra el contenido del archivo |
| tail | muestra parte final de un archivo | tail prueba muestra el final de ese archivo |
| head| muestra el inicio de un archivo | head prueba muestra el inicio de ese archivo |
| cp | copiar archivoc | cp prueba crea otro archivo con el mismo contenido |
| mv | mueve archivos | mv prueba1 Documents/ mueve ese archivo a la carpeta Documents |
| adduser | crea usuario nuevo | sudo adduser goku crea un usuario nuevo con ese nombre |
| sudo passwd | cambia la contrasena de un usuario| |
| history | muestra el historial d elos comando utilizados | |
| history / grep (comando) | muestra momentos donde el comando fue utilizado | |
