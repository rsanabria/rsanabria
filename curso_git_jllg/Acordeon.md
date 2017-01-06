# Acordeón Git

### $ git init 
-Inicializa un nuevo repositorio

### $ git status
-Muestra estado actual de repositorio, saber si contiene archivos o si están listos para ser registrados

### $ git add
-Empieza a seguir a uno o más archivos y los agrega al área de preparación generando un nuevo estado de nuestro proyecto. La bandera -A agrega todos los archivos del repositorio

### $ git add <archivo> | -A
-Prepara un archivo para nuevas etapas

### $ git commit
-Registra nuestro nuevo estado y lo registra en la historia de nuestro repositorio. Por lo general se usa con la bandera -m y un pequeño texto que describa lo que hicimos.

### $ git commit [-m "descripcion"]
-Guarda el nuevo estado en el historial del repositorio

### $ git log
-Muestra el historial de commits que hemos hecho en nuestro proyecto. La bandera --oneline muestra cada entrada en una sola línea. También es posible ver la historia de un sólo archivo, pasando como argumento el nombre de éste.

### $ git log [ --oneline <archivo>]
-Muestra el historial completo de commits del repo o de un archivo en específico.

### .gitignore
-Este archivo nos permite ignorar archivos o directorios (como los .exe o a.out de un programa) los cuales no queramos que entren en el seguimiento del repositorio.    -nombres de archivos o carpetas separados por saltos de línea    -wildcards*

### $ git checkout
-Este comando nos permite movernos entre commits o incluso ramas de nuestro repositorio. LLeva como argumento el id del commit o parte de.

### $ git revert
-Este comando nos permite revertir un cambio ya registrado creando un nuevo commit. Lleva como argumento el id del commit a revertir.

### $ git reset
-Regresa al último estado guardado borrando permanentemente cualquier cambio en el área de pruebas que se hiciera con add. Lleva la bandera --hard

### $ git clean
-Borra permanentemente los archivos no seguidos, es decir los que no se han agregado con add. LLeva la bandera -f.

### $ git branch
-Lista ramas existentes en el repositorio. Si se agrega el nombre [<nombre>]
de rama como argumento se creará una rama con ese nombre pero no se pasa a esa, para pasarse se usa checkout.

### $ git merge
-Fusiona dos ramas, fusiona una rama objetivo con la rama donde nos encontramos actualmente. Recibe como parámetro la rama objetivo.

### $ git diff
-Muestra lo corregido en el archivo

### Conflictos de merging
-A veces sise está trabajando en 2 ramas al mismo tiempo, modificando un mismo archivo, se pueden generar conflictos  por lo que es necesario corregirlos.

### Repositorio remoto
-Es aquel que se encuentra alojado en un servidor externo a nuestro computador. Un repositorio remoto puede ser accedido por uno o varios colaboradores. El repositorio puede ser centralizado o distribuido.

### $ git remote
-Permite hacer diversas operaciones sobre repositorios remotos. -add: agrega un nuevo remoto. -remove: elimina un remoto.

### $ git remote add <nombre> <url>
### $ git remote remove <nombre>

-Por lo general el nombre del repositorio remoto es: origin

### $ git pull
-Permite recibir el último estado registrado del repositorio remoto. Recibe como argumentos el nombre del remoto y del branch al que queremos hacer pull.

### $ git push
-Permite mandar los cambios registrados de nuestro repositorio local a un repositorio remoto. Recibe como argumentos el nombre del remoto y del branch al que queremos hacer push.

### $ git clone <ruta> [<nombre local>]
-ruta es la url del repo de github y ek nombre de la carpeta local donde se va a clonar

### Pull Request
-Este método permite a los equipos de desarrollo controlar qué cambios se realizan en un repositorio. El propietario del repositorio recibe peticiones de cambio, las cuales deben ser aprobadas por él. Típicamente un colaborador hace fork del proyecto maestro y al realizar sus cambios realiza pull request. 

### Issues
-Ofrece la capacidad de crear entradas en nuestro repositorio, las cuales pueden ser usadas para especificar varias cosas, desde mejoras al sistema, problemas a resolver o nuevas ideas que implementar.


