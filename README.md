# Comandos útiles de Git

1.  git init // inicializar mi repositorio git > 'working directory'
2.  git add . // prepara todos los archivos para la foto o commit > 'staging area'
3.  git reset . // anula la acción anterior
4.  git commit -m "Primer commit" // hace la foto o commit > 'repository'
5.  git checkout -- . // reconstruye todos los archivos a la foto del último commit
6.  git log // tengo todo el listado de los commit
7.  git commit --amend // i=para editar y escape, :wq!=para que edite y cierre inmediatamente.
8.  git checkout -b rama-heroes // Crear una nueva rama
9.  git checkout master // volvemos a la rama principal
10. git branch -d rama-heroes // borrar rama heroes
11. git push // subir cambios a github
12. git commit -am "Readme actualizado" // realiza el add y commit a la vez

## Otras notas

-   git branch // ver ramas
-   git checkout master // volvemos a la rama principal
-   git merge rama-heroes // fusionar la rama heroes al master
-   git pull // descargar los cambios hechos por otros usuarios
-   git clone // clonar repositorio a mi equipo
-   git status // ver el estado de tus archivos

## Subir a GitHub

-   git remote add origin https://github.com/sologuillesosa/prueba-heroes.git
-   git branch -M main
-   git push -u origin main

## Primera configuración

-   git config --global user.email "sologuillesosa@gmail.com"
-   git config --global user.name "Guillermo Sosa"

> Fernando Herrera Youtube: https://www.youtube.com/watch?v=iT4UOkyI09k&ab_channel=FernandoHerrera
> GitHub: https://github.com/Klerith/youtube-git
