1- Compilació:

	javac Prjava02.java
	
2- Execució:

	cd ..
	java prjava02.Prjava02

Comandos por pregunta:
1 - git branch branca00

5 - git checkout main
    git status
    git log

7 - git checkout branca00

10b - git merge branca00

12 - git push -u origin main

14a - git push -u branca01


Respostas Práctica:
6 - Desde el IDE, en mi caso VSCode, al ejecutar el comando git checkout main deja de ser visible la línea 28 añadida, ya que las ramas tienen un historial distinto, y la modificación de esta línea se hizo en la rama 'branca00'. En la rama main nunca se hizo, así que no se encuentra en el archivo.

7 - Al volver a la rama branca00, se puede ver nuevamente en el archivo la línea modificada pues es en esta rama donde se hizo el cambio. 

12c - Sólo se actualiza la rama main, por que antes de hacer push se hizo merge de branca00 con main. Así que a efectos de git, estas ramas contienen las mismas versiones de los archivos, con la única diferencia que en main hay un commit más. Como son iguales en este punto, el push actualiza solamente la rama main. Además, el push se hizo en la rama main, de manera que en el repositorio remoto no hay evidencias de la existencia de branca00

14c - La rama branca01 está a 1 commit de distancia de la rama main, es decir uno por delante. Ya que hicimos cambios y un commit que no se hizo en main.
