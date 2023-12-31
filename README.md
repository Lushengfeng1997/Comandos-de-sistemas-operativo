# Comandos-de-sistemas-operativo
Sistemas Operativos
# Bitácora de comandos para la clase de sistemas operativos

| Comando                     | Descripción                                        | Ejemplo de uso          |
|-----------------------------|----------------------------------------------------|----------------------------------------------------|
| `clear` | Limpia la pantalla de la sesión de consola actual. | `clear` muestra toda la información (gracias al flag `-a`) sobre 
| `cd <ruta de directorio>` | Cambia el directorio actual | `cd ~/Ulacit` para ir a una carpeta llamada Ulacit en el home (~) del usuario actual. |
| `ls <directorio>` | Lista los archivos y directorios que están dentro de un directorio. Si no se pasa ningún directorio cómo parámetro se listan los del directorio actual. | `ls ~/Ulacit` para mostrar todas las carpetas y archivos dentro de la carpeta Ulacit. |
| `cp <origen> <destino>` | Copia un archivo (o directorio si se usa el flag `-r`) de un origen a un destino. | `cp -r ~/Ulacit/* ~/` para copiar todo el contenido de la carpeta llamada Ulacit al home del usuario actual. |
|`echo`| Imprime en pantalla una cadena de texto. | `echo "Hola"` imprimiría Hola en la salida de la terminal. |
|`pwd` | Muestra el directorio actual. | `pwd` imprimiría la ubicación. ~ulacit$: pwd /home/lfeng118|
|`whoami` | Muestra solo el nombre en el sistema | `whoami` imprimiría el nombre del usuario como root. ~ulacit~$:whoami lfeng118|
|`su` | Ejecuta la schell sustituyendo al usuario logeado, lo puede transformarse en el usuario root si tiene la contraseña. |`su` se solicita el password: root: |
|`man` | Manual en línea, el comando "man" permite acceder al manual en línea de Linux. | Para consultar sobre un comando. |  
|`mkdir` | Crea un directorio. | ~ulacit:`mdfir` [directorio] crea un directorio en Home /home/directorio/ | 
|`rndir` | Borra el directorio. | ~ulacit: `rmdir` [directorio] Borra el directorio de home /home/ |
| `. ` | Directorio actual|~ulacit: `ls .`  /carpeta actual|
|`ls -l` | Lista de los archivos y carpetas de un directorio de manera detallada. | ~ulacit: `ls -l` -rw-r--r-- 1 usuario usuarios 1024 Jul 23 12:30 archivo.txt |
| `mv` | El comando mv permite mover archivos o directorio, o cambiarles el nombre. | ~ulacit:  `mv `[file] origen destino. |
| `rm` | Borrar archivos o directorios. | ~ulacti: `rm` [file] |
|`remana` | cambiar el nombre a un conjunto de archivos. | ~ulacit: `rename` "." /home/directorio |
| `more` | Despliegue en pantalla el contenido de uno o más archivos. | ~ulacit: `more *` Muestra las informaciones de los archivos. | 
|` less ` | Permite el retroces. | ~ulacit: less [archivos] Despliega el archivo largo. | 
| `cat` | Concatena archivos y los muestra en la salida. | ~ulacit: `cat -n`/etc/password -n numera todas las líneas. |
| `find` | Busca el camino hacia abajo en la estructura de archivos, para buscar los archivos que cumplan con la condición especificada. | ~ulacit: `find /var -user "takayama" -name "d"` "name" nombre de archivo "b" archivo |
| `chmod` | Modificar el permiso. | ~ulacit: `chmod g-r` mi.archivo -Quitar el permiso de lectura al grupo. | 
|`umask` | Modificar los valores de los permisos por defecto. | ~ulacit: `umask 022` Con un umask de 022, los permisos asignados a los nuevos archivos serán 644. |
| `chown` | Cambiar el usuario o grupo propietario de un archivo o directorio. | Asignar el usuario y grupo ~ulacit: chown usrl: usrl file | 
| `set` | Permite la modificación de variables del shel y la lista de todas las variables locales. | ~ulacit; set.  lista todas las variables. | 
|`split` | Forma varios archivos a partir de uno. | ~ulacit: split -[bcla] [prefijo] -a utiliza sufijos de longitud, -b byte escribe BYTES en cada fichero de salida. -c escribe un máxomo de bytes sin cortar líneas. | 
| `kill` | "kill" envía una señal a un cierto proceso. El uso más es para terminar un proceos corriendo en el sistema. | ~ulacit: `kill` [-señal] Se termina el proceso. | 
|`sudo apt update && sudo apt upgrade`| Actualizar los repositorios del sistema. | ~ulacit: `sudo apt update && sudo apt upgrade` [sudo] contraseña para lfeng118: (requiere la contraseña del usuario "root" para actualizarlo. | 
|`wget https://git.io/vpn -O openvpn-ubuntu-install.sh` |Comando para instalar la aplicación de VPN.| ~ulacit: wget https://git.io/vpn -O openvpn-ubuntu-install.sh --2023-06-15 --https://git.io./vpn/ 
|`chmod -v +x openvpn-ubuntu-install.sh` | El comando para descomprimir el paquete de "vpn".| ~ulacit: chmod -v +x openvpn-ubuntu-install.sh 2023-06-21 saved |
|`ip addr show` | Muestra la dirección de IP. | ~ulacit: ip addr show la direción de ip se despliega en la pantalla. | 
|`sudo openvpn  --config /root/(nombre de archivo).ovpn`| Comando para configurar la aplicación en el sistema operativo. | ~ulacit: sudo openvpn  --config /root/osaka.ovpn  se configura y se establece la conexión en el sistema operativo | 
|`sudo chmod 777 root` | Comando para dar el privilegio a la carpeta "root". | ~~ulacit:sudo chmod 777 root    ~ulacit:  | 
|`‘sudo chmod +r osaka.ovpn` | Comando para habilitar el permiso de mover el archivo. | ~ulacit: ‘sudo chmod +r osaka.ovpn ~ulacit: | 
|`sudo pacman -Sy` | Actualizar los paquetes en el sistema operativo. | ~ulacit:`sudo pacman -Sy` ~ulacit:actualizado... |
|`sudo pacman -S unrar zip unzip gzip bzip2` | Instalar nuevos paquetes para comprimir y descomprimir archivos. | ~ulacit:sudo pacman -S unrar zip unzip gzip bzip2 ~ulacit:~~~ |
|`sudo pacman -S yay && sudo yay -S --needed base-devel` | nstalar el Repositorio AUR (Arch User Repository). Este repositorio permite tener acceso a otros paquetes de software que no están disponibles en el repositorio principal de Manjaro. | 
|`yay -S google-chrome` | Instalar google-chrome por medio del instalador de paquetes yay. | ~ulaci: yay -S google-chrome |
|` sudo pacman -S apache` | Instalar Apache para configurar le archivo de html. | ~ulaci: sudo pacman -S apache |
| `hhtps:http://localhost/` | Acceder la página de index de servidor. | Utilizar el navegador para acceder |
| `uname -a` | Verificar el kernel que está utilizando el SO. | ~ulacit: uname -a |
| `git clone https://github.com/mortasoft/linux-scripts` | Utilizar el link de github para crear una copia de la carpeta en el servidor. | ~ulacit:git clone https://github.com/mortasoft/linux-scripts ( es importante cambia el link por el link de su carpeta. | 
|`sudo useradd -m nombredeusuario -G wheel -p passworddelusuario` | Comando para agregar un nuevo usuario. | ~ulacit: `sudo useradd -m nombredeusuario -G wheel -p passworddelusuario` (Reemplazar el nombreusuario y la contraseña por lo que quiera. | 
| `mkdir dirtres` | Crear una carpeta | ~ulacit: mkdir dirtres (dirtres es nombre de la carpteta.) 1 
| `ls /bin` | Salida del comando. | ~ulacit: ls /bin > guardar.txt Utilizar el carácter < o > para guardar en un archivo. | 
| `ls -la /etc/a* > $HOME/dir003/dircuatro/archivo2` | Crear un archivo en determinado lugar. | ~ulacit:`ls -la /etc/a* > $HOME/dir003/dircuatro/archivo2` La ruta de destinatorio. |
|`ls -l $HOME 1> $HOME/dir003/dircuatro/archivo3`| El comando para crear un archivo en la carpeta dircuatro. | ~ulacit: ls -l $HOME 1> $HOME/dir003/dircuatro/archivo3 ~ulacit: |
|`sudo cp -r/etc/a*/home/manjaro/dirdos`| copie todos los archivos de /etc cuyo nombre comience con “a“ a la carpeta dirdos. | ~ulacit: sudo cp -r/etc/a*/home/manjaro/dirdos  "manjaro" nombre del usuario y "dirdos" la carpeta destino del archivo. | 
|`mv /home/manjaro/diruno/archivo0 /home/manjaro/dir004/` | Mover un archivo hacia un cierto lugar que desee. | ~ulacit:`mv /home/manjaro/diruno/archivo0 /home/manjaro/dir004   Ruta de archivo original, la ruta de archivo destino. |
|`sudo chmod 600 Dirdos` | El usuario1 es el dueño de la carpeta y tiene permisos de escritura y lectura. Los otros usuarios no tienen ningún permiso. | ~ulacit: sudo chmod 600 Dirdos ~ulacit:  "DIrdos" nombre de la carpeta. |
|`sudo chmod 060 dir003` | El usuario2 es el dueño de la carpeta y tiene permisos de escritura y lectura. Los otros usuarios no tienen ningún permiso. | ~ulacit:sudo  chmod 060 dir003 |
| `sudo chmod 006 dir004` | El usuario3 tiene permisos de escritura, lectura y ejecución y los otros usuarios tienen permisos de escritura y lectura. | ~ulacit: sudo chmod 006 dir004|
|`history > historial.txt` | Guardar el historial de todos los comandos digitados en un archivo llamado historial.txt. | ~ulacit: history > historial.txt |
|`nano Script_01.sh` | utilizar el archivo de nano para crear un archivo de bash. | ~~ulacit: nano Script_01.sh |
| `bash Script_01.sh` | El comando para correr el archivo de bash directamente. | ~~ulacit: bash Script_01.sh | 
|`sudo apt install apt-transport-https \ ca-certificates curl gnupg-agent software-properties-common`| Instalar dependencias | ~ulacit:sudo apt install apt-transport-https \ca-certificates curl gnupg-agent software-properties-common|
|`sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"` |Agregar el repositorio oficial de Docker. | ~ulacit:sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable" |
|`sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose` | Instalar Docker. | ~ulacit:sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose |
|`sudo usermod -aG docker ${USER}` | Ejecutar Docker sin sudo. | ~~ulacit:sudo usermod -aG docker ${USER} | 
|`sudo systemctl start docker` o `sudo systemctl enable docker` | Ejecutar Docker al iniciar el equipo. | ~ulacit:sudo systemctl start docker |
|` sudo docker run hello-world` | Probar que funcione con el comando. | ~ulacit: sudo docker run hello-world |
|`docker pull wordpress` | Descarga la imagen del contenedor. | ~ulacit:docker pull wordpress |
|`docker images` | Ver imágenes instaladas. | ~ulacit: docker images |
|`docker run ubuntu` | Ejecuta un nuevo contenedor usando una imagen. | ~ulacit:docker run ubuntu |
|`sudo docker ps -a` | Ver el estado de los contenedores. | ~ulacit: sudo docker ps -a |
|`sudo  docker start d9b100f2f636` | Inicia un contenedor en estado detenido | ~ulacit: sudo  docker start d9b100f2f636 |
|`docker rmi Image Image` | Eliminar imagenes de docker | ~ulacit:docker rmi Image Image|
|`sudo  docker stop d9b100f2f636` | Detiene un contenedor que esté corriendo. | ~ulacit: sudo  docker stop d9b100f2f636 |
|`docker rm ID` | Eliminar contenedores. | ~ulacit:Eliminar contenedores | ~ulacit:docker rm ID |  
|`docker run --rm image_name` | Eliminar contenedor después de cerrado. | ~ulacit:docker run --rm image_name | 
|`sudo docker rm $(sudo docker ps -a -f status=exited -q)` | Eliminar todos los contenedores “Exited (0)” | ~ulacit:sudo docker rm $(sudo docker ps -a -f status=exited -q) |
|`docker pull portainer/portainer-ce:latest` | Obtener la imagen docker de Portainer. | ~ulacit:docker pull portainer/portainer-ce:latest | 
|`sudo docker volume create portainer_data` | Crear un volumen donde se almacenarán los datos de configuración de Portainer. | ~ulacit:sudo docker volume create portainer_data |
|`sudo docker run -d -p 8000:8000 -p 9443:9443 --name=portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/dataportainer/portainer-ce:latest` | Ejecutar la aplicación con el puerto 9443 y el puerto 8000 expuesto. |~ulacit:sudo docker run -d -p 8000:8000 -p 9443:9443 --name=portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce:latest |
|` https://localhost:9443/#!/auth` | Abrir en el navegador la URL de Portainer.| 
|`sudo docker stop portainer` | Detener el "portainer". | ~ulacit:sudo docker stop portainer |
|`sudo docker rm portainer` | Eliminar el "portainer" . | ~ulacit: sudo docker rm portainer | 
|`sudo docker rm volume portainer` | Eliminar el volume de portainer. | ~ulacit:sudo docker rm volume portainer |
