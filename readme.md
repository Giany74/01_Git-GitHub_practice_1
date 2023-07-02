***
- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog -> lista todos los commit
git checkout <hash> -> recupero el commit borrado

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
Tube que hacer un commit de main y luego desde la rama styled hacer un merge de main

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
el conflicto radica en que los 2 archivos git-nuestro.md son distintos

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
ningun conflicto se hizo un merge fast-forward

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph --oneline

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
el merge fast-forward se ejecuta cuando no hay cambios en la rama de destino, en este caso sería un fast 
forward. Para hacer un no fast forward hay que usar el comando git merge --no-ff {{rama_a_fusionar}}

- ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?
git checkout <hash> .

- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
git reflog para seleccionar el hash y git merge <hash>

- ¿Qué comando o comandos usaste en el paso 32?
git branch <hash commit inicial>

- ¿Qué comando o comandos usaste en el punto 33?
git branch <hash estado final>
***
