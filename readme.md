<br>
- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
<br>
git reset --hard HEAD~1
<br>
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
<br>
git reflog -> lista todos los commit
<br>
git checkout 'hash' -> recupero el commit borrado
<br>
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
<br>
Tube que hacer un commit de main y luego desde la rama styled hacer un merge de main
<br>
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
<br>
el conflicto radica en que los 2 archivos git-nuestro.md son distintos
<br>
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
<br>
ningun conflicto se hizo un merge fast-forward
<br>
- ¿Qué comando o comandos utilizaste en el paso 25?
<br>
git log --graph --oneline
<br>
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
<br>
el merge fast-forward se ejecuta cuando no hay cambios en la rama de destino, en este caso sería un fast forward. Para hacer un no fast forward hay que usar el comando git merge --no-ff 'branch'
<br>
- ¿Qué comando o comandos utilizaste en el paso 27?
<br>
git reset HEAD~1
<br>
- ¿Qué comando o comandos utilizaste en el paso 28?
<br>
git checkout 'hash'.
<br>
- ¿Qué comando o comandos utilizaste en el paso 29?
<br>
git branch -D title
<br>
- ¿Qué comando o comandos utilizaste en el paso 30?
<br>
git reflog para seleccionar el hash y git merge 'hash'
<br>
- ¿Qué comando o comandos usaste en el paso 32?
<br>
git checkout 'hash commit inicial'
<br>
- ¿Qué comando o comandos usaste en el punto 33?
<br>
git checkout 'hash estado final'
