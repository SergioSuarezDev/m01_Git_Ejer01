# Respuestas Preguntas

- ¿Qué comando utilizaste en el paso 11? git reset HEAD~1 
¿Por qué? Porque con este reset sería suficiente para recuperar el ultimo commit.

- ¿Qué comando o comandos utilizaste en el paso 12? 
git reflog y git reset 6019b1b
¿Por qué? Primero reflog para buscar el commit y despues el reset para volver a el.

- El merge del paso 13, ¿Causó algún conflicto? No ¿Por qué? Porque no habia la mismas lineas modificadas en ambos ficheros dentro de las dos ramas.

- El merge del paso 19, ¿Causó algún conflicto? Si. ¿Por qué? Porque habia la mismas lineas modificadas en ambos ficheros dentro de las dos ramas.

- El merge del paso 21, ¿Causó algún conflicto? No ¿Por qué? Porque no habia la mismas lineas modificadas en ambos ficheros dentro de las dos ramas.

- ¿Qué comando o comandos utilizaste en el paso 25? git log --all --graph

- El merge del paso 26, ¿Podría ser fast forward? No ¿Por qué? Porque se ha creado un nuevo commit y master apunta el, sin embargo title apunta a otro commit. 

- ¿Qué comando o comandos utilizaste en el paso 27? git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28? git checkout .

- ¿Qué comando o comandos utilizaste en el paso 29? git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30? git reflog y git reset --hard e7b6c58

- ¿Qué comando o comandos usaste en el paso 32? git reset --hard 0e3721d

- ¿Qué comando o comandos usaste en el punto 33? git reset --hard 1b0be58

