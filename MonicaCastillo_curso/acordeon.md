
#Acordeon Git
### $git init
    -inicializa un repositorio
### $git status
    -Muestra el estado actual de nuestro repositorio, permite saber si el repositorio contiene archivos de seguimineto, o si estan listos para estar registrados.
### $git add <archivo> | -A
    Este comando empieza a seguir a uno o más archivos generando un nuevo estado de nuestro proyecto.
    la bandera -A agrega todos los archivos del repositorio
### $git commit [-m "descripcion"]
    Este comando registra nuestro nuevo estado y lo registra en la historia de nuestro repositorio
    Por lo general este comando se usa con la bandera  -m y un pequeño texto que describa lo que hicimos.
    
### $git log
    Este comando nos muestra el historial de commits que hemos hecho en nuestro     proyecto 
    -La bandera --oneline muestra cada entrada en una sola linea
    -tambien es posible ver la historiqa de un solo archivo, pasando como           argumento el nombre de éste.
    
#### $.gitignore
    
    - Este archivo nos permite ignorar archivos o directorios los cuales no            queramos que entren en el seguimiento de nuestro repositorio.
        -nombres de archivos o carpetas
        -wildcards*
#### $git checkout

    - Este comando nos permite movernos entre commits o incluso ramas de nuestro repositorio

lleva como argumento el  id del commit o parte de.
#### $git revert

    - este comando nos permite revertir un cambio ya registrado, creando un nuevo commit
    lleva como argumento el id del commit a revertir
### $git reset

    Regresa al único estado guardado, borrando permanentemente cualquier cambio en el área de pruebas.
    
    -lleva la bandera --hard
### $git clean
    Borra permanentemente los archivos  NO seguidos
    -lleva la bandera -f
 
Branch

Una rama branch es, en pocas palabras, una linea independiente de trabajo, la cual no afecta a nuestra rama principal (master), sin embargo, tiene la capacidad

### $git branch
    Lista las ramas existentes en el repositorio
    - si se le agrega [<nombre>] de rama como argumento, se creará una rama con ese nombre
    
#### $git merge
    Este comando fusiona dos ramas, fusiona una rama objetivo con la rama donde     nos encontramos actualmente.
    -recibe como parámetro la rama objetivo
    
### Conflictos de merging
    A veces si se esra trtabajando en 2 ramas al mismo tiempo, modificando un mismo archivo, se pueden generar conflictos, por lo que es necesario corregirlos.

### ¿QUE ES UN REPOSITORIO REMOTO???

Es aquel que se encuentra alojado en un servidor externo a nuestro computador.
un repositorio remoto puede ser accedido por uno o varios colaboradores. El repositorio puede ser centralizado o distribuido

### $git remote
este comando nos permite hacer diversas operaciones sobre repositorios remotos
-add: agrega un nuevo remoto
-remove: elimina un remoto

 $git remote add <nombre> <url>
 $git remote remove <nombre>
 
 *Por lo general el nombre del repositorio es origin

### $git pull
Este comabndo nos perm,ite recibir el ultimo estado registrado
del repositorio remoto
-recibe como argumentos el nombre del remoto y del branch al que queremos hacer pull

### $git push

este comando nos permite mandar los cambios registrados de nuestro repositorio local a un repositorio remoto
-recibe como argumentos el nombre del remoto y del barnch que queremos hacer pull

### $git clone <nombre repositorio a clonar>

### Fork 
    - Es parecido a un clon

### Pull Request
-Este método permite a los equipos de desarrollo controlar que cambios se realizan en un repositorios.
-El propietario del repositorio recibe peticiones de cambio,las cuales deben ser aprobadas por el.
-Tipicamente un colaborador hace fork del proyecto maestro, y al realizar sus cambios realiza el pull request.
-También es posible hacer pull request entre ramas.

### Issues

GitHub ofrece la acapacidad de crerar entradas en nuestro repositorio, las cuales pueden ser usadas para especificar varias cosas, desde mejoras al sistema, problemas a resolver
    
    
    
    
    
    
    
    
    
    
    

