# Acordeón Git

#### $ git init
- Inicia un nuevo repositorio.

### $ git status
- Muestra el estado actual de nuestro repositorio,
nos permite saber sie el repositorio contiene archivos
osin seguimiento o si están listos para registrarlos.


### $ git add
Este comando empieza a seguir a uno o más archivos y los agrega al ára de preparación, generando un nuevo estado de
nuestro proyecto.

La bandera -A agrega todos los archivos al repositorio.
### $ git log
Este comando nos muestra el hitorial de commits que hemos hecho en nuestrro proyecto.
- La bandera --online muestra cada entrada en una sola línea.
- También es posible ver la historia de un solo archivo, pasando como argumento el nombre de este.

### .gitignore
Este archivo nos permite ignorar archivos o directotios los cuales no queramos que entren en el seguimiento de nuestro repositorio, por ejemplplo, los ejecutables de los archivos en C que no queramos guardar. que solo queramos el codigo fuente.

### $ git commit [-m "descripción"]
Este comando registra nuestro nuevo estado y lo registra en la historia de nuestro repositorio.

Por lo general este comando ese usa con la bandera -m y un pequeño texto que describa lo que hicimos.

### $ git checkout
Este comando nos permite movernos entre commits o incluso ramas de nuestro repositorio.
- Lleva como argumento el id del commit o parte de él.


### $ git revert
- Este comando nos permite revertir un cambio ya registrado, creando un nuevo commit.
- Lleva como argumento el id del commit a revertir.

### $ git reset
Regresa al último estado guardado, borrando permanentemente cualquier cambio en el área de pruebas.
- Lleva la bandera --hard

### $ git clean
Borra permanentemente los archivos a los cuales les hiciste cambios desde el commit anterior, esto incluye tanto adiciones como cambios que no se adicionaron.

### Branch
Una rama(branch) es, en pocas palabras, una línea independiente de trabajo, la cual no afecta a nuestra rama principal(master), sin embargo, tiene la capacidad de fusionarse con otras ramas, incluida la principal.


### $ git branch
Lista las ramas existentes en el repositorio.

- Si se le agrega [nombre] de rama como argumento, se creará una rama con ese nombre.
- Se puede poner la rama git checkout -b "Nombre de la nueva rama a crear".

### $ git merge
Este comando fusiona dos ramas, fusiona una rama objetivo con la rama donde nos encontramos actualmente.
- recibe como parámetro la rama 

### $ git diff
Muestra clos cambios en los archivos que no se han agregado con add pero que podrian agregarse.

### Conflictos de merging
- A veces si se esta trabajando en 2 ramas al mismo tiempo, modificando un mismo archivo, se pueden generar conflictos, por lo que es necesario corregirlos.


### Repositorio remoto
Un repositorio remoto es aquel que se enecuentra alojado en un servirdor externo a nuestra computadora. Un repositorio remoto puede ser accedido por uno o varios colaboradores.
Le repositorio puede ser centralizado o distribuido.

### $ git remote
Este comando nos permite hacer diversas operaciones sobre repositorios remotos.
- add: agrega un nuevo remoto.
- remove: elimina un remoto.

$ git remote add <nombre> <url>
$ git remote remove <nombre>

En general, el nombre del repositorio remoto es: origin

### $ git pull
Este comando nos permite recibir el último estado registrado del repositorio remoto.
- recibe como argumentos el nombre del remoto y el branch que queremos hacer pull.

### $git push
Este comando nos permite mandar los cambios registrados de nuestro repositorio local a un repositorio remoto.
- Recibe como argumentos el nombre del remoto y del branch al que queremos hacer push.


### Fork
Github ofrece una opción que nos permite copiar el repositorio de algún otro usuario y hacerlo nuestro.

### Pull Request
- Este método pemite a los equipos de desarrollo controlar que cambios se realizan en un repositorio.
- El propietario del repositorio recibe peticiones de cambio, las cuales deben ser aprobadas por él.
- Típicamente un colaborador hace fork del proyecto maestro, y al realizar sus cambios realiza el pull request.
- También es posible hacer pull request entre ramas.

### Issues
Github ofrece la capacidad de crear entradas en nuestro repositorio, las cuales pueden ser usadas para especificar varias cosas, desde mejoras al sistema, problemas a resolver o nuevas ideas a implementar.



















