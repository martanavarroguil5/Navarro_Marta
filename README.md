# Navarro_Marta
1º Con un Pull Request un usuario puede fusionar en su repositorio los cambios que otro usuario ha solicitado hacer en el repositorio del primer usuario.

2º Un conflicto de fusión se da cuando al realizar un merge un mismo archivo presenta un contenido distinto en la misma linea. Para solucionarlo uno debe abrir dicho archivo y eliminar de la linea la información que quiere cambiar. Por último, se continúa con el merge con git merge --continue.

3º Estando en la rama examen_parcial escribes el comando "git merge main" en la consola, seguramente salten conflictos con algún archivo, se resuelven los conflictos editando el archivo. Una vez editado lo guardas en el índice con "git add <archivo>" y haces un commit "git commmit -m <mensaje>" Se continúa el merge con "git merge --continue". Luego te cambias a la rama main con "git checkout main", una vez en main vuelves a hacer el merge y no deberían saltar conflictos. Terminado el proceso subes los cambios al repositorio remoto con "git push origin main".

4º Para esta situación utilizaría el comando "git reset <código del commit>" que devuelve el proyecto al estado de ese commit manteniendo los cambios con el del estado actual. Para ver el código del commit anterior utilizaría "git log --oneline" que lista todos los commits realizados y sus códigos. 

5º Un fork se realiza dando en el botón fork de un repositorio ajeno, con esto creas un nuevo plano de trabajo de ese repositorio sin modificar los cambios del repositorio original. Esto se suele utilizar cuando se trabaja en grupos y una persona debe hacer modificaciones a mi proyecto pero yo no quiero que me lo estropee. Una vez mi compañero ha actualizado su repositorio forked puede solicitarme fusionar su repositorio en el mío con un Pull Request.

6º a) Para llegar a dicho arcivo utilizaría el comando "cd /marta_navarro(raíz)/Universidad/UAX/archivo.txt". Se trata de una ruta absoluta porque pasa por todos los nodos intermedios entre el directorio raíz hasta el archivo.
b) En este caso utilizaría el comando "cd /UAX/archivo.txt". Es una ruta relativa porque no inicia desde el directorio raiz.

7º 1) b) git clone 2) b) git checkout (añadiendo la opción -b) 3) c) git checkout 4) b) git add 5) b) git commit 6) b) git push 7) c) git pull 8) d) git merge 9) a) git reset -hard 10) c) git log

8º Primero fusionaría la rama matemáticas y develop, para esto, estando en la rama matemáticas, escribo el comando "git merge develop" en la consola. Si saltan conflictos los resuelvo editando los archivos, añado el archivo al índice "git add archivo" y hago un commit "git commit -m <mensaje>", continúo el merge "git merge --continue". Luego me cambio a la rama develop con "git checkout develop" y vuelvo a hacer merge "git merge matemáticas". Una vez estén fusionadas las ramas, las subo al repositorio remoto con "git push origin develop". Para continuar, hago la fusión de la rama diseño UX. Me cambio a la rama diseño UAX con "git chcekout diseño UX". Una  vez en la rama hago "git merge develop". Si saltan conflictos los resuelvo editando los archivos, añado el archivo al índice con "git add archivo" y hago un commit "git commit -m <mensaje>", continúo el merge "git merge --continue". Luego me cambio a la rama develop con "git checkout develop" y vuelvo a hacer merge "git merge diseño UX". Cuando ambas ramas se hayan fusionado sin conflictos, subo las ramas al repositorio remoto con "git push origin develop". Así quedarían las dos ramas matemáticas y diseño UX integrads y fusionadas en la rama develop. 

9º C) Añadiste el botón "x^4" al archivo "index.html" en tu repositorio local, creaste un commit con los cambios y luego subiste el repositorio local al remoto en la rama principal (master).

Link al repositorio: https://github.com/martanavarroguil5/Navarro_Marta.git
