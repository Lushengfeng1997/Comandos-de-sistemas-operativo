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


