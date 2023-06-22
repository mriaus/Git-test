##This is a repo for the git practice in the mobile bootcamp with keepcoding

There are the questions with the answers:

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
	
	En el paso 11 se debe deshacer el último commit, perdiendo los cambios por lo que debemos utilizar 2 comando diferentes
	**git reset HEAD~1**  para deshacer el commit seguido de **git restore git-nuestro.md** para eliminar los cambios en el 
	fichero

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
		
	**git reflog** para saber los hash y **git reset --hard 029f6bd** para restaurarlo

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

	No, al hacer la rama desde main y no haberla actualizado, no existen conflictos y se actualiza la rama

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

	Si, como ambas ramas han salido de main y ambas han coincidido varias modificaciones los cambios se pisan y tenemos que elegir
 	con que nos quedamos o modificar el fichero para que no se pisen

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

	No, styled era una versión mas actualizada de main y ya habiamos hecho merge de main a styled anteriormente

- ¿Qué comando o comandos utilizaste en el paso 25?

	**git log --graph**

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

	Si, ya que hemos cambiado solo la parte inicial del documento y mantiene todo lo de 
	master sin bifurcaciones

- ¿Qué comando o comandos utilizaste en el paso 27?

	**git reset HEAD~1**

- ¿Qué comando o comandos utilizaste en el paso 28?

	**git restore git-nuestro.md**

- ¿Qué comando o comandos utilizaste en el paso 29?

	**git branch -D title**

- ¿Qué comando o comandos utilizaste en el paso 30?

	**git reflog**
  
	**git reset 13554f4**

- ¿Qué comando o comandos usaste en el paso 32?

	**git reflog**
  
	**git reset 755efa3**

- ¿Qué comando o comandos usaste en el punto 33?

	**git reflog**
  
	**git reset 13554f4**
