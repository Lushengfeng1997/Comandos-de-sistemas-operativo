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


