# Acordeón Git

### $ git init
 - Inicializa un nuevo repositorio

### $ git status
- Nos muestra el estado actual de nuestros archivos

### $ git add <archivo> | -A
 - Este comando empieza a seguir a uno o más archivos y los agrega al área de preparació, generando un nuevo estado de nuestro proyecto.
 - La bandera -A  suma todos los que estén en nuestro repositorio
 
### $ git commit
- registra nuestro nuevo estado y lo registra en la historia de nuestro repositorio. Se usa generalmente con -m y un pequeño texto que describa lo que hicimos.

### $ git log [ --oneline <archivo>]
- Muestra el historial de commits que hemos hecho en nuestro proyecto.
- --oneline muestra cada entrada en una sola línea
- Escribiendo el nombre del archivo muestra los commits de ese archivo.

### .gitignore
- Archivo que nos permite ignorar archivos o directorios los cuales no queremos que entren en el seguimiento de nuestro repositorio.
- Contenido: nombres de archivos (se puede utilizar el wildcard *)

### $ git checkout
- Permite movernos entre commits o incluso ramas de nuestro repositorio. Como argumento se introduce el id del commit o parte de él.

### $ git revert <id>
- Revierte un estado, generando un nuevo commit.

### $ git reset
- Regresa al último estado guardado, borrando permanentemente cualquier cambio en el área de pruebas. Lleva la bandera --hard . Antes del commit (los add)

### $ git clean
- Borra permanentemente los archivo no seguidos. Lleva la bandera -f

### Branching
git branch [<rama>]
- Lista las ramas existentes en el repo
- Crea una nueva rama si le pasa un argumento (nombre de la rama)

### Merging
git Merge <rama_objetivo>
- Une dos ramas

Conflictos de merging
- A veces si se está trabajando con 2 ramas al mismo tiempo, modificando un mismo archivo, se pueden generar conflictos, por lo que hay que corregirlos.

### Repositorio remoto
-Es aquel que se encuentra alojado en un servidor externo.
- Puede ser centralizado o distribuido

### Github
- Es un servicio de repositorio distribuido

### $ git remote
- Permite hacer diversas operaciones sobre repositorios remotos.
- add: agrega un nuevo remoto
- remove: elimita un remoto
     $ git remote add <nombre> <url>
     $ git remote remove <nombre>
- Por lo general el nombre del repositorio es "origin"
- Ejemplo: $ git remote add origin https://github.com/Sandlafi/sandlafi.github.io

### $ git pull
- Permite recibir el último estado registrado del repositorio remoto.
- Recibe como argumentos el nombre del remoto y del branch al que queremos hacer pull
- Ejemplo: $ git pull origin master

### $ git push 
- Permite mandar los acmbios registrados de nuestro repositorio local a un repositorio remoto
- Recibe como argumentos el nombre del reoto y del branch al que queremos hacer push.
- Ejemplo: $ git push origin master

### git clone  <URL colaborador> <nombre>
- Crea un clone del repositorio compartido con el colaborador. 
- Ejemplo: $ git clone https://github.com/MonicaCastillo/monycastillo.fi.github.io RepColabMoni
- Crea un directorio-repositorio llamado <nombre>

### Fork
Github ofrece una opción, la cual nos permite copiar el repositorio de otra persona

### Pull Request
- Este método permite a los equipos de desarrollo controlar qué cambios se realizan en un repositorio.
- El propietario del repositorio recibe peticiones de cambio, las cuales deben ser aprobadas por él
- Típicamente un colaborador hace fork del proyecto maestro,y al realizar sus cambios realiza el pull request
- También es posible hacer pullrequest entre ramas

### Issues
Github ofrece la capacidad de crear entradas en nuestro repositorio,las cuales pueden ser usadas para especificar varias cosas,desde mejoras al sistema, problemas a resolver o nuevas ideas que implementar.




