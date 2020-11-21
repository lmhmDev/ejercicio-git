-¿Qué comando utilizaste en el paso 11? ¿Por qué?

*git reset --hard HEAD~1* porque *git reset HEAD~1* deshace el ultimo commit en el
repositorio sin modificar el **Working copy**, usando *--hard* tambien revierte los cambios
en el Working copy.

-¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

Primero he usado *git reflog* para encontrar el commit anterior, luego he usado
*git reset @id* para volver de nuevo al commit.


-El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No causo ningún conflicto porque fue un merge fast-forward, los cuales no pueden
tener conflictos.

-El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Si hay conflicto porque es un merge no fast-forward, por lo tanto si tienen archivos
comunes con contenido diferente da conflicto, hay que modificar uno de los dos para
que se puedan unir las ramas


-El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No da conflicto porque es un merge fast-forward


-¿Qué comando o comandos utilizaste en el paso 25?

*git log --graph --oneline*


-El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Si porque forman parte de una lista (forman parte de la misma "bifurcación")

-¿Qué comando o comandos utilizaste en el paso 27?

*git reset HEAD~1*

-¿Qué comando o comandos utilizaste en el paso 28?

*git reset*

-¿Qué comando o comandos utilizaste en el paso 29?

*git branch -D title*

-¿Qué comando o comandos utilizaste en el paso 30?

*git reflog* para ver donde esta el merge, *git checkout @hash*, *git commit*
para rehacer el commit


-¿Qué comando o comandos usaste en el paso 32?

*git reflog* para ver el hash del primer commit, *git reset @hash* para ir hacia el

-¿Qué comando o comandos usaste en el punto 33?

*git reflog* para ver el hash del ultimo commit, *git reset @hash* para ir hacia el
