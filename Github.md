# Comandos de Github en Git

Github es un sitio de internet donde puedes subir los proyectos que creas usando git. Aunque ambos no son iguales.

![Github no es Git](https://i.blogs.es/0bdd9c/github/450_1000.jpg)

Los comandos se usan para subir el código de tus proyectos a esta página web.

1. Añadir repositorio remoto

~~~
git remote add origin url
~~~

2. Ver rpositorios remotos

~~~
git remote -v
~~~

3. Eliminar repositorio remoto

~~~
git remote rm origin
~~~

4. Añadir cambios LOCAL -> REMOTO

~~~
git push -u origin master
~~~

5. Al revés (REMOTO -> LOCAL)

~~~
git pull -u origin master
~~~

6. Ver ramas remotas

~~~
git branch -r
~~~

7. Ver todas las ramas

~~~
git branch -a
~~~

8. Clonar un repositorio remoto

~~~
git clone url
~~~

## Dar seguimiento a las ramas remotas

* LOCAL -> REMOTO

~~~
git push ...
~~~

* REMOTO -> LOCAL

- Sincronización y unión

~~~
git fetch origin
git merge origin/master
~~~

- En un paso

~~~
git pull
~~~

## Operaciones con ramas remotas

* Creación

~~~
git push -u origin rama_remota
~~~

* Copia

~~~
git checkout -b local remoto
~~~

* Eliminación

~~~
git push origin --delete rama_remota
~~~
