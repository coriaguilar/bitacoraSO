# bitacoraSO
Bitácora de Comandos Sistemas Operativos
| Comando | Descripción | Ejemplo de uso |
|--|--|--|
|`ls`| Lista los directorios | `ls` muestra una lista de los directorios del programa. |
|`ls -al`| Lista los directorios con los archivos ocultos | `ls -al` muestra una lista de los directorios del programa incluyendo los archivos ocultos. |
|`cd`| Cambia la ruta del directorio actual | `cd Documentos` cambia al directiorio Documentos. |
|`pwd`| Muestra la ruta del directorio actual | `pwd` si se encuentra en la carpeta "Documentos" muestra /home/usuario/Documentos. | 
|`mkdir`| Crea un nuevo directorio | `mkdir NuevoDirectorio` crea un directorio llamado "NuevoDirectorio". |
|`~`| Muestra el directorio personal del usuario | `cd ~` muestra el directorio "Home". |
|`rm`| Elimina archivos y directorios | `rm archito.txt` elimina el archivo.txt. |
|`chroot`| Cambia el directorio de raiz para un ejecutar un proceso aislado | `chroot` |
|`chmod`| Cambia los permisos de un archivo | `chmod 644 archivo.txt` modifica los permisos para el archivo llamado archivo.txt. |
|`usermod`| Modifica la configuracion del usuario | `sudo usermod -aG grupo usuario` agrega un usuario a un grupo. | 
|`chown`| Cambia el propietario y el grupo de un archivo o directorio chown` usuario archivo.txt | `chmod 644 archivo.txt` modifica los permisos para el archivo llamado archivo.txt. |
|`adduser`|Añade un nuevo usuario|sudo `adduser` nuevo_usuario|
|`ps`| Muestra informacion sobre los procesos en ejecucion | `ps aux` muestra todos los procesos del sistema. |
|`top`| Muestra la información en tiempo real sobre los procesos y la carga del sistema | `top` abre una ventana que muestra información sobre los procesos en ejecución y otros detalles. |
|`apt-get`|Gestiona los paquetes de software |`apt-get install firefox` instala el software Firefox. |
|`sudo`| Ejecuta comandos con privilegios de superusuario | `sudo apt-get update` actualiza el sistema. |
|`passwd`| Cambia la contraseña de un usuario | `sudo passwd usuario` cambia la contraseña de usuario. |
|`date`| Muestra la fecha y hora actual |`date` muestra la fecha y hora actuales en el formato predeterminado. |
|`cal`| Muestra el calendario | `cal 2023` muestra el calendario del año 2023. |
|`kill`| Comando que termina un proceso |`kill +PID` termina el proceso PID. |
|`df`| Muestra información sobre el uso de espacio en disco |`df -h` muestra la información en gigabytes (GB) y megabytes (MB). |
|`ifconfig`| Muestra la información sobre las interfaces de red del sistema | `ifconfig` |
|`ssh`| Se conecta a un servidor remoto a través del protocolo SSH  |`ssh + informacion del servidor` |
|`cp`| Copia archivos o directorios | `cp archivo.txt ~/Documentos/` copia el archivo.txt en Documentos. |
|`mv`| Mueve o renombra archivos o directorios |`mv archivo.txt ~/Documentos/` mueve el archivo.txt a Documentos. |
|`cat`| Muestra el contenido de un archivo sin abrirlo |`cat archivo.txt` muestra el contenido del archivo.txt. |
|`tar`| Crea y manipula archivos comprimidos en fomato .tar | `tar -xvf archivo.tar` descomprime y extrae el contenido del archivo.tar. |
|`zip`| Crea archivos comprimidos en fomato .zip | `zip archivo.zip` crea el archivo.zip. |
|`unzip`| Descomprime archivos comprimidos en fomato .zip |`unzip archivo.zip` descomprime el archivo.zip. |
|`nano`| Edita archivos de texto | `nano archivo.txt` |
|`vim`| Editor de texto avanzado en la terminal | `vim archivo.txt` edita el archivo.txt. |
|`history`| Muestra el historial de los comandos ejecutados en la sesion actual | `history` |
|`echo`| Muestra mensajes en la terminal |`echo "Prueba"` muestra Prueba. |
|`reboot`| Reinicia el sistema operativo Linux | `reboot` |
|`find`| Busca archivos y directorios en el sistema | `find` |
|`curl`| Realiza solicitudes HTTP desde la linea de comando y obtiene contenido de una URL | `curl URL` obtiene contenido de la pagina URL |
|`du`| Muestra el uso de espacio en disco por directorio| `du -h directorio` |
|`scp`| Copia archivos de forma segura entre sistemas remotos |`scp origen destino`|
|`hostname`| Muestra o cambia el nombre del sistema |`hostname` muestra el nombre del sistema en la terminal. |
|`nano`| Crea y edita archivos de texto .txt | `nano prueba.txt` crea el archivo prueba.txt. |
|`clear`| Limpia la pantalla de la sesión de consola actual | `clear` |
|`man ls`| Muestra los parametros de un comando | `man ls`|
|`su`| Cambia el usuario al superusuario | `su` |
|`sudo pacman -Sy`| Se usa para actualizar la lista de los paquetes disponibles en los repositorios y sincronizar la informacion|`sudo pacman -Sy`|
|`sudo pacman -S yay`| Instala el programa "yay" | `sudo pacman -S yay` |
|`yay -S google-chrome`| Se utiliza para instalar Google Chrome en la distribucion de Linux Manjaro |`yay -S google-chrome`|
|`sudo systemctl start httpd`| Se utiliza en Manjaro para iniciar el servicio del servidor web Apache (HTTPD) |`sudo systemctl start httpd` |
|`uname -a`| Brinda información detallada sobre el sistema operativo y el hardware en el que estás trabajando | `uname -a` |
