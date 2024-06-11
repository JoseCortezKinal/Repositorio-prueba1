Subir los cambios a github

git add . → Añadir los cambios al repositorio local

git commit -m "" → Añade un comentario para identificar los cambios

git push -u origin master → Añade los cambios al repositorio remoto


--------------------------------------------------------------
git init → Inicializar un repositorio local

git remote add origin {URL} → añadir el repositorio remoto al local

git pull origin master → traer los cambios del remoto al local


--------------------------------------------------------------
Pasos para hacer merge:
	- traer la rama a la que quiero hacer merge 
	- git fetch
	- git checkout {Rama_fusion}
	*nota la rama activa, debe a la que quiero hacer merge
	*recomendado, hacer pull de la rama antes del merge.
	- git merge {nombre_rama_a_fusionar}.
	*opcional git commit -m "merge"
	- git add .
	- git push -u origin {Rama_fusion}.
