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
