Respuestas a las preguntas:
 - ¿Qué comando utilizaste en el paso 11? ¿Por qué?
	git reset --hard HEAD~1
	para que se vaciara el working copy.
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
	git reset --hard <numero de commit>
	Para mover tanto el puntero como la rama donde estaban.
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
	git merge main
	No causa conflicto, ya que style ya tenia todo lo que estaba en main.
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
	si hay conflicto, porque son 2 romas con el mismo archivo modificado.	
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
	No, era fast forward
- ¿Qué comando o comandos utilizaste en el paso 25?
	git log --graph	
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
	sí, podria ser ff, todos los commits de styled estaban ya en title
- ¿Qué comando o comandos utilizaste en el paso 27?
	git reset HEAD~1
- ¿Qué comando o comandos utilizaste en el paso 28?
	git restore git-nuestro.md	
- ¿Qué comando o comandos utilizaste en el paso 29?
	git branch -D title
- ¿Qué comando o comandos utilizaste en el paso 30?
	git reset --hard <numero de commit>
- ¿Qué comando o comandos usaste en el paso 32?
	git reset --hard <numero de commit>
- ¿Qué comando o comandos usaste en el punto 33
	git reset --hard <numero de commit>
