# Acordeon Git

### $ git init
- Inicializa un nuevo repositorio

### $ git status
- Muestra el estado actual de nuestro repositorio, nos permite saber si el repositorio contiene archivos sin seguimiento, o si están listos para ser registrados 

### $ git add
- este comando empieza a seguir a uno o más archivos y los agrega al área de preparación, generando un nuevo estado de nuestro proyecto. La bandera -A agrega todos los archivos repositorio. $ git add <archivo> || -A 
- prepara un archivo para nuevas etapas

### $ git commit [-m "descripcion"] 
- Este comando registra nuestro nuevo estado y lo registra en la historia de nuestro repositorio. Por lo genereal este comando se usa con la bandera -m y un pequeño texto que describa lo que hicimos.

### $ git log
- Este comando nos muestra el historial de commits que hemos hecho en nuestro proyecto.
-- La bandera --oneline muestra cada entrada en una sola línea.
-- También es posible ver la historia de un solo archivo, pasando como argumento el nombre de éste

### $ .gitignore
- Este archivo nos permite ignorar archivos o directorios los cuales no queramos que entren en el seguimiento de nuestro repositorio. por ejemplo los ejecutables de archivos de C que no queramos guardar, que sólo queramos el codigo fuente


### Deshaciendo Comandos
### $ git checkout
- Este comando nos permite movernos entre commits o incluso ramas de nuestro repositorio
--Lleva como argumento el ID del commit o parte de.

### $ git revert ["direccion del commit"]
- Se esta trabajansdo sobre la hiustorio de mi repositorio
- Revierte un estado, generando un nuevo commit

# $ git reset --hard
- Deshace permanentemente los cambios del área de preparación

### $ git clean -f
- Borrar permanentemente lso archivos no seguidos por git


### Branch
- Una rama es , en pocas palabras, una línea independiente de trabajo, la cual no afecta 

# $ git branch [<nombre>]
- Lista las ramas existentes en el repositorio.
-- Si se le agrega [<nombre>] de rama como argumento, se reará una rama con ese nombre.

# $ git merge
- Este comando fusiona dos ramas, fusiona una rama objetivo con la rama donde nos encontramos actualmente.
-- Recibe como parametro la rama objetivo

# $ git diff
- Muestra los cambios efectuados en el codigo que se este trabajando en el momento


# Conflictos cde merging
- A veces se está trabajando en 2 ramas al mismo tiempo, modicficando un mismo archivo, se pueden generar conflictos, por lo que es necesario corregirlos


