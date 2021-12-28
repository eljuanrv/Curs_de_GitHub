# Curs_de_GitHub
Partes mas reelevantes del curso

## Gist

new->newgist

- Pequeños ejemplos de codigo

¿Cuando Usar?
- Cuando necesito mostrar un fragmento de codigo a un colaborador
- Tutorial de codigo y quiero desplegar el ejecicio en una pagina externa
- Si quiero mostrar codigo a algun grupo y no quiero mostrar mi repositorio privado

## Repositorio Local
Utilizando Git Bash en Windows
1. Creas una carpeta donde quieras crear tu repositorio
2. abres Git Bash
3. Incresas el comando ``` $ cd ``` seguido por la ruta de tu carpeta **Puedes arrastrar la carpeta al Git Bash para obtener la ruta**
4. Ingresas el comando ``` $ git init ```
5. Para conocer el estatus de un repositorio ingresas ``` $ git status ```
6. Para añadir una archivo a nuestro repositorio primero lo movemos a la carpeta creada y despues ponemos el comando ``` $ git add . ``` el cual agregara todos los archivos que tengamos en la carpeta y no se han agregado al repositorio
7. Para incluir la versión del archivo en el repositorio usamos ``` $ git commit -m "MENSAJE"``` -m se utiliza para añadir un mensaje para comprendel las modificaciones 
8. Cuando eliminas un archivo se usa nuevamnte el ``` $ git add . ``` para cambiar su nevo status

## Enviar Repo Local a GitHub
1. Abrimos Git Bash y apuntamos a la carpeta que tiene nuetro repositorio
2. Nos aseguramos que todos los archivos esten guardados correctamente
3. Ponemos el comando ``` git remote add origin ``` seguido de la URL de nuestro repositorio *.git*
4. Y listo ahora ese repositorio remoto se encuentra relacionado con nuesrto proyecto (los archivos no se encuentran en la nube pero ya podemos enviarlos)
5. Para enviar los archivos usamos ``` git push -u origin master ``` 

## Utilizar Cliente de GitHub

*Se puede conectar con GitHub*

Es para un ambiente grafico más intuitivo
1. Descargar GitHub Desktop desde [Here](https://desktop.github.com/)

Tenemos 3 comandos basicos
1. Clonar: es para clonar un repo que se encuentre en GitHub, simplemente seleccionas el repo y le das clonar, despues eliges la ruta de almacenamiento y realizas algun cambio en la carpeta del repo local, despues reresal a GitHub desktop y haces el commit, y por ultimo haces el push to origin
2. Crear: crear un repo a partir de archivos de tu equipo, seleccionamos la opcion de nuevo repositorio, Ingresamos l nombre, la descripción y el readme y listo, despues seleccionamos publish para cargarlo a GitHub
3. Agregar: aagregar algun repo que ya tenes en tu equipo
4. Sincronizar Repositorios: Para sincronizar GitHub Deskton con GitHub antes de hacer cualquier cambio en Local debes de hacer click en *Fetch Origin* para asgurarte de que tienes la ultima version del archivo y si no es así hacemos *Pull* para descargarla
5. Crear Branches, primero creamos una nueva rama, despues vamos y editamos algun archivo, y en el commit se puede observar que se va a hacer a la nueva rama, y por ultimo le damos en *Publish Branch* para subir la rama a GitHub 
6. Fusionar Branches: Selecccionamos la rama principal, y ahí mismo seleccionamos la opcion *Choose a branch to merge into main* y despues damos click en *create a merge commit* y por ultimo damos click en *publish* para actualizar GitHub
7. Delete branches: seleccionamos la branch y despues desplegamos las opciones de la pestaña *branch* y seleccionamos *delete* y podemos eliminar la branch tanto en local como en GitHub solo seleccionamos la opción




