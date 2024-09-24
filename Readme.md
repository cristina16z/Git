<img src="git_banner.jpg">



<br></br>
<h1 style="text-align: center;">CONFIGURACIÓN BÁSICA</h1>


Añadir nombre que saldrá en los commits

```bash
  git config --global user.name "[nombre]"
```
\
Añadir email que saldrá en los commits

```bash
  git config --global user.email "[email]"
```


<br></br>
<h1 style="text-align: center;">INITIAL COMMANDS</h1>


Iniciar Repositorio 

```bash
  git init
```
\
Clonar Repositorio

```bash
  git clone [https..]
```
\
Saber el estado

```bash
  git status
```
\
Añadir el Git Ignore
```bash
  git add .gitignore
```
\
Eliminar un archivo (no del staging area, sino del proyecto)
```bash
  git rm [nombreArchivo_queDeseas_Eliminar.extensión]
```
\
Añadir un único archivo al staging area

```bash
  git add [nombreArchivo.ext]
```
\
Añadir todos los archivos al staging area

```bash
  git add .
```

\
Commit

```bash
  git commit -m "[comentario]"
```
\
Añadir todos los archivos + Commit

```bash
  git commit -am "[comentario]"
```
\
Actualizar lo que tienes en el repositorio a tu local

```bash
  git pull
```

\
Push

```bash
  git push
```



<br></br>
<h1 style="text-align: center;">BRANCHES</h1>

Crear Rama

```bash
  git branch [nameBranch]
```
\
Moverte hacia una Rama

```bash
  git checkout [nameBranch]
```
\
Crear rama y moverte hacia ella a la vez

```bash
  git checkout -b [nameNewBranch]
```
\
Hacer el push de la nueva rama
```bash
git push --set-upstream origin [nameNewBranchCreated]
```
\
Eliminar una rama por completo
```bash
git branch -D [nameBranchWantEliminate]
```
\
Fusionar Ramas: Situarte en la rama que quieres los cambios (master)
```bash
git merge [nameBranch_queQuieres_Fusionar]
```
\
?
Guardar los cambios
```bash
git push origin master 
```
\
? Fusionar Ramas
```bash
git merge [RamaOrigen] [RamaDestinoMaster]
```
\
? Cambiar nombre de una Rama
```bash
git branch -m [nombreAntiguo] [newNameBranch]
```






<br></br>
<h1 style="text-align: center;">RESTORE OR REVERT</h1>


Quitar todos los archivos del staging area

```bash
  git reset
```
\
Volver a un commit anterior: mirar el identificador del commit que quieres volver y moverte hacia él

```bash
  git log
```
```bash
  git checkout [identificador_commit 995b16z..]
```
\
Restaurar un archivo eliminado del proyecto (anteriormente no se hizo ningún commit)
```bash
  git restore [nombreArchivo.ext]
```

<br></br>
<h1 style="text-align: start;">AUTHORS ✒️</h1>

*[@Cristina16z](https://github.com/cristina16z)*

