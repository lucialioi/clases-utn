# empezamos desde 0:

    -git init
    -git add .   (es para agregar los archivos) 
    -git commit -m "agregar descripcion"
    -git branch -M main (cambia el nombre de la rama master a main)

**se crea un repositorio en github, new repositori, public, poner el nombre y se crea el link**

    git remote add origin "el link del repositorio nuevo ya hecho"
    git push -u origin main (voy a enviar de forma remota lo q se este haciendo/añadido a una parte de main)
una vez hecho esto se abre un cadradito de logueo asi verificar si somos nosotros pusheado, ya sea el dueño o los colaboradores 

con esto tenemos el repo subido a github

# para actualizar 
se pone control s y la bolita blanca va a desaparecer luego se pone los siguientes comandos:  
git add .
git commit -m "nuevo"
git push

luego se refleja en el github

# si nos equivocamos al poner git remote usamos el comando
git remote set-url origin <url_correctao> una vez puesto esto se pone git push -u origin main 