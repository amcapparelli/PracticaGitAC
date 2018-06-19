# respuestas al ejercicio 1

1- En el paso 11 utilicé el comando git reset --hard HEAD~1 porque quería volver al commit anterior perdiendo los cambios
en mi working copy.

2- En el paso 12 utilicé primero el comando git reflog y luego el comando git reset --hard (y la referencia del commit), 
porque quería rehacer el último commit y recuperar los cambios también en el working copy

3- En el paso 13, el merge no dio ningún conflicto, ya que la rama styled
contenía los commit de la rama master y por eso el mensaje fue *Already up to date*

4- En el paso 19 el merge causó conflicto porque las mismas líneas en la rama
styled y en la rama htmlify tenían modificaciones respecto a su commit ancestro común.

5- En el paso 21 el merge no causó conflictos porque el commit
donde estaba la rama master pertenece también a la rama styled

6- En el paso 25 utilicé el comando git log --garph

7- El merge del paso 26 podría haber sido fast forward porque
los commits de master están contenidos también dentro de la rama title

8- En el paso 27 utilicé el comando git reset HEAD~1

9- En el paso 28 utilice el comando git checkout -- git-nuestro.md

10- En el paso 29 utilicé el comendo git branch -D title

11-En el paso 30 utilicé el comando git reflog, luego el comando git reset --hard (y la referencia del commit)

12- En el paso 32 utilicé git checkout y el hash del commit inicial

13- En el paso 33 utilicé git checkout master

