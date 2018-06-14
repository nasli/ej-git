# ejercicio1


- ¿Qué comando utilizaste en el paso 11? ¿Por qué?  
  `git reset --hard` Porque elimina sin dejar cambios en el working copy directory

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?  
  `git reflog` `git reset --hard 7ce9b76` Para obtener el hash del commit y rehacerlo.  

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?   
  No, porque no hay cambios entre ellos, styled ya tenía todos los cambios de master, branch Already up-to-date. 

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?  
  Sí, porque las dos ramas editan las mismas líneas del fichero git-nuestro

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?  
  No, es un merge Fast-forward, forman una lista

- ¿Qué comando o comandos utilizaste en el paso 25?  
  `git log --graph --pretty=oneline` 

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?  
  Sí, podía ser fast forward porque forman una lista, title es hijo de master

- ¿Qué comando o comandos utilizaste en el paso 27?  
  `git reset HEAD~1`

- ¿Qué comando o comandos utilizaste en el paso 28?  
  `git checkout -- git-nuestro.md`

- ¿Qué comando o comandos utilizaste en el paso 29?  
  `git branch -D title` 

- ¿Qué comando o comandos utilizaste en el paso 30?  
  `git reset reflog`  `git reset --hard fc16dd2`

- ¿Qué comando o comandos usaste en el paso 32?  
  `git reflog` `git reset --hard e1569ae`

- ¿Qué comando o comandos usaste en el punto 33?  
  `git reflog` `git reset --hard fc16dd2`
