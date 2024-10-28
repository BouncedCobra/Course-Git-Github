# Course-Git-Github

## Comandos

Para revisar la version de git

* git --version

Para ver la ayuda

* git help
* git --help < Nombre del comando >

Para salir de "q"

Para configurar un usuario

* git config --global user.name "tu nombre"
* git config --global user.email "tu correo"
* git config --global -e

Iniciar un repositorio

* git init

Ver segimiento de archivos

* git status

Remover archivos del seguimiento

* git reset < Nombre del archivo >

Regresar el proyecto a el commit anterior

* git checkout -- .

Agregar archivos al seguimiento

* git add < Nombre del archivo >

Agregar todos los archivos al seguimiento

* git add .

Hacer un commit

* git commit -m "Mensaje"

Ver los commits

* git log

Ver los commits de una manera mas visual

* git log --oneline

Ver los commits de una manera mas visual y con los nombres de las ramas

* git log --oneline --decorate

Cambiar el nombre de un commit

* git commit --amend -m "Mensaje"

Regresar al commit anterior

* git reset --soft HEAD^

Regresar al commit anterior y quitar los archivos del seguimiento

* git reset HEAD^

Regresar al commit anterior y quitar los archivos del seguimiento y eliminar los cambios

* git reset --hard HEAD^

## Notas

Si ejecutar un comando no regresa un mensaje es que se hizo correctamente

Para salir de la ventana de edicion de texto es con "esc" y luego ":wq!"
