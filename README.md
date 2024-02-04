# GIT2

● ¿Qué comando utilizaste en el paso 11? ¿Por qué?
	-El comando usado fue **reset --hard HEAD~1**, siendo el *--hard* el que elimina los cambios
	en el *Working copy* y *HEAD~1* la indicacion de que retoceda el puntero 1 posicion.

● ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
	-Primero se utiliza el comando **reflog** para ver el número identificador del commit que se	 
	deshizo en el paso anterior, y despues se usa un **reset --hard** seguido del número
 	identificador para restaurarlo.	

● El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
	-Existe el conflicto *"Allready up to date"* por que las dos ramas están ya sincronizadas.

● El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
	-Resulta un conflicto porque hay diferencias en los archivos *git-nuestro.md*.

● El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
	-Se hace un merge *Fast Forward* porque las dos ramas están en la misma lista.

● ¿Qué comando o comandos utilizaste en el paso 25?
	-El comando usado es **log --graph**.

● El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
	-Si podría ser ff, ya que sigue siendo una sola lista.

● ¿Qué comando o comandos utilizaste en el paso 27?
	-**reset HEAD~1** es el comando usado.

● ¿Qué comando o comandos utilizaste en el paso 28?
	-**reset --hard <número identificador del commit>** es el comando usado.

● ¿Qué comando o comandos utilizaste en el paso 29?
	-**branch -D** es el comando usado.

● ¿Qué comando o comandos utilizaste en el paso 30?
	-**reset --hard <número identificador del commit>** es el comando usado.

● ¿Qué comando o comandos usaste en el paso 32?
	-**checkout <número identificador del commit>** es el comando usado.

● ¿Qué comando o comandos usaste en el punto 33?
	-**reflog** seguido de **checkout <número identificador del commit> es el comando usado.

   **Nota**: Siempre que un commit desaparece del log, se usa el comando reflog para primero localizarlo
   y poder extraer el número identificador del commit, como en el último caso.
