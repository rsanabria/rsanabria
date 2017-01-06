# Acordeón Git

### $ git init
    -inicializa un nuevo repositorio

### $ git status
    -Muestra el estado actual del repositorio

### $ git config --global user.name
    -Establece el nombre del desarrollador

### $ git config --global user.email
    -Indica el correo electronico del desarrollador

### $ git config  --global core.editor
    - Indicar el editor por default

### $ add
    -  empieza seguir uno o mas archivos :
         -A agrega todos los archivos delrepositorio

### $ git commit
    -  registra el nuevo estado y loregistra enlahistoria del repositorio
        -m <Descripcion del cambio>

### $ git log 
    - muestra la historia de commits que sehan hecho en un proyecto
        --online muestra cada entrada en una sola linea
        <archivo> se muestra  la historia solo de ese archivo

.gitignore
	-Este archivo nos permite ignorar archivos o directorios que no queramos darles seguimientos 


### git checkout <-idcommit> 
	- Regresas alestado seleccionado
	con el parametro -b crea la ramay te pociciona en ella.
	
### git revert <-idcommit>
	- revierte cambios realizados en ese estado

### $ git reset 
	-Resgresa al ultimo estado guardado, borrando permantemente cualquier cambio en el area depruebas
	- lleva labandera --hard

### $ git clean -f 
	- Borra permanentemente los archivosnoseguidos 


### $ git branch
	- lista las ramas existentes en el proyecto
	<nombre> se crea la rama con ese nombre 

### $ git diff 
	muestra  los cambios que se han hecho en los archivos.

### $ git merge 
	- fusiona dosramas un la actual con una objetivo

### $ git pull 
	- regresa el ultimo estado registrado del repositorio remoto
	- recibe como argumentos el nombre del remoto y del branch al que queremos hacer pull

### $ git push 
	-manda los cambios registrados de un repositorio local a un remoto 
	- recibe como argumengtos el nombre del repositorio remoto y del branch al que queremos hacer push

###  Fork 
	- te permite copiar un repositorio remoto a tu repositorio remoto en gitHub

### Issue
	-Es un modo de generear alertas en un repositorio 


