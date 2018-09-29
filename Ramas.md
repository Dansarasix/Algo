# Comandos de ramas en git

Las ramas en git se usan para separar la línea principal del proyecto de forma que se puedan trabajar en otras versiones del software sin pisar la principal.

![Ejemplo de Ramas](https://www.paradigmadigital.com/wp-content/uploads/2016/08/Git4.jpg)

Los siguientes comandos se usarán para trabajar ramas en proyecto de git:

1. Ver las ramas listadas:

~~~

git branch

~~~

2. Crear una rama

~~~

git branch nombre_rama

~~~

3. Cambiarnos de rama

~~~

git checkout nombre_rama

~~~

4. Hacer pasos 2 y 3 al mismo tiempo

~~~

git checkout -b nombre_rama

~~~

5. Comparar ramas

~~~

git diff nombre_rama...nombre_rama

~~~
