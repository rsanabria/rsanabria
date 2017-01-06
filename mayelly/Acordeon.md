# Acordeón Git

### $ git init
  * Inicializa un nuev repositorio.
 
### $ git status
        -Muestra el estado actual de nuestro repositorio, nos permite saber si el repositorio contiene archivos de seguimiento, o si estan listos para estar registrados.

### $ git touch
   crear nuevo archivo
### $ git add
  Este comando empieza a seguir a uno o más archivos generando un nuevo estado de nuestro proyecteo
 la bandera -A agrega a todos los arhivos del repsitorio

### $ git add <archivo> | -A
 - prepara un arcivos para nuevas etapas.
 
### $ git commit (-m "descripcion)
  -Este comando registra nuestro nuevo estado y lo registra en la historia de nuestro repositorio.
Por lo general este comando s eusa con la bandera -m  y un pequeño texto que describa lo q hicimos.

## $ git log (--oneline <archivo>)
- Este comando nos muesta el historial de comits que hemos hecho en nuestro proyecto.
        - La bandera --oneline muestra cada entrada en una sola línea.
        - También es posible ver historia de un solo archivo, pasando como argumento el nombre de éste.
        
-Muestra el historial completo de commits del repo, o de un archivo si se especifica.

###  .gitignore
- Este archivo nos permite ignorar archivos o directorios los cuales no queramos que entren en el seguimiento de nuestro repositorio.
        - nombres de archivos o carpetas
        - Wildcards * (extensiones)

### $ git checkout
-Este comando nos permite movernos entre commits o incluso ramas de nuestro repositorio.
        -Lleva como argumento el id del commit o parte de.
        
### $ git revert
-Este comando nos revierte un cambio ya registrado, creando un nuevo comit.
        -Lleva como argumento el id del commit a revertir.
## $ git reset

-Regresa al último estado guardado, borrando permanentemente cualquier cambio en el área de pruebas
    -lleva la bandera --hard
## $ git clean 
-Borra permanentemente los archivos no seguidos.
    -lleva la bandera  -f
## $ branch    
        Una rama (branch) es, en pocas palabras, una línea independiente de trabajo, la cual no afecta a nuestra rama principal (master), sin embargo, tiene la capaidad de fusionarse con otras ramas, incluida la principal.

##  $ git branch
-Lista las ramas existentes en el epositorio.
    -si se le agrega [<nombre>] de rama con ese nombre
## $ git mege

-Este comando fusiona dos ramas, fusiona una rama objetivo con la rama donde nos encontramos actualmente.
 -recibe como párametro la rama objetivo
 * git branch inicio
 * *git checkout inicio
 * se sustituyen o hace lo mismo 
        *   git checkout -b inicio
        *  git diff 
        *       -muestra que cambios se hicieron
## conflictos de merging
a vecs sis e está trabajando en 2 amas al mismo tiempo, modificam¿ndo un archivo,se puede generar conflictos, por lo q es necesario corregirlos.
# git branch -D nombre archivo

-para borrar una rama

## $ git remote

-Este comando nos permite hacer diversas  operaciones sobre repositorios remotos

--add: agrega un nuevo remoto

--remove: elimina un remoto

     $ git remote add <nombre> <url>
     $ git remote remove <nombre>
     por lo general el nombre del repositorio remoro es: origin

## $ git pull
Este comando nos permite recibir el ultimo estado registradodel repositorio remoto.
--recibe como argumentos el nombre del remoto y del branch al que queremos hacer pull

## $ gitpush

Este comando nos permite mandar cambios registrados de nuestro repositorio local a un repositorio remoto.
--recibe como argumentos el nomre del remoto y del branch al que que queremos hacer pull.

## $git clone

git clone y direccion donde esta la carpeta a clonar

para hacer un revert despues de haber hecho un commit se hace primero un pull despues un revert y luego un push

---Pull Request

-este metodo permite a los equipos de desarrollo controlar que cambios se realizan en un repositorio
--el propietario del repositorio recibe peticiones de cambio, las cuales deben ser aprobadas por el.
-tipicamente un colaborador hace fork del proyecto maestro, y al realizar sus cambios realiza pull request.
-tambien es posible hacer pull request entre ramas

----issues

github ofrece la capacidad de crear entradas en nuestro repositorio, las cuales pueden ser usadas para especificar varias cosas, desde mejoras del sistema, problemas a resolver o nuevas ideas a implementar.





