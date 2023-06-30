* ¿Qué comando utilizaste en el paso 11? ¿Por qué?  
Se utilizó el comando `git reset --hard HEAD~1`. Con esto se deshace el
último commit y los cambios realizados en el Working copy.


* ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?  
Primero se utilizó `git reflog` para saber el ID del commit al que
queremos regresar y a continuación se hizo `git reset --hard ID` para 
recuperarlo.


* El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?  
No causó ningún conflicto, se usó el comando `git merge main`

 
* El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?  
Sí causó conflicto porque el archivo git-nuestro.md es distinto en
cada uno de los commits de la rama styled y htmlify. Se modifica
el archivo y se deja con la versión de la rama styled.


* El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?  
No causó conflictos porque el archivo git-nuestro.md no contiene líneas
distintas.


* ¿Qué comando o comandos utilizaste en el paso 25?  
Se utilizaron los comandos `git log --branches --graph --oneline`
para poder ver correctamente el diagrama de las ramas.


* El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?  
Sí podría haber sido fast forward porque no se perdería acceso a ningún commit.


* ¿Qué comando o comandos utilizaste en el paso 27?  
Se utilizó primero el comando `git reflog` para saber el ID al que 
queremos regresar y a continuación `git reset ID` para deshacer el 
último commit sin perder cambios en el Working copy.


* ¿Qué comando o comandos utilizaste en el paso 28?  
Se utilizó el comando `git restore git-nuestro.md` para descartar los 
cambios.


* ¿Qué comando o comandos utilizaste en el paso 29?  
Se utilizó el comando `git branch -D title`


* ¿Qué comando o comandos utilizaste en el paso 30?  
Se utilizó primero el comando `git reflog` para saber el ID al que
queremos regresar y a continuación se hizo `git reset --hard ID` para
restaurar todos los cambios. Por último se vuelve a crear la rama "title"
con `git branch title` y se hace el merge no fast forward con `git merge --no-ff title`


* ¿Qué comando o comandos usaste en el paso 32?  
Se utilizó `git reflog` para saber el ID del commit al que queremos regresar
y a continuación se hizo `git reset --hard ID`

* ¿Qué comando o comandos usaste en el punto 33?  
Igual que en el punto 33, se utilizó `git reflog` para saber el ID del
commit al que queremos regresar y a continuación se hizo `git reset --hard ID`
