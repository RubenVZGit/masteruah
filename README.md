# masteruah
*Repositorio de la practica GIT*

Ejercicio 2
- Clonamos con "git clone https://github.com/RubenVZGit/masteruah.git"

Ejercicio 3 (Commit Inicial)
- Iniciamos git con "git init"
- Vamos a iniciar sesion con un usuario "git config --global user.name 'tu nombre'"
- Seguidamente nuestro correo "git config --global user.email 'tu@email.com'"
- Utilizamos "git add masteruah/README" para añadir el archivo
- Y finalmente con "git commit -m "commit inicial""

Ejercicio 4 (Push Inicial)
- Con el comando "git push" subimos el commit que habíamos realizado al repositorio remoto.

Ejercicio 5 (Fichero 1.txt)
- Añadimos el fichero con "nano 1.txt"

Ejercicio 6 (Tag v0.1)
- Añadimos el tag con "git tag v0.1"

Ejercicio 7 (Subimos todo al repositorio remoto)
- Ejecutamos "git add 1.txt"
- Ejecutamos "git add README.md"
- Ejecutamos "git commit -m "Commit 2""
- Ejecutamos "git push"
- Ejecutamos "git push origin v0.1" (Para añadir tag v0.1)

Ejercicio 8 (Crear una rama v0.2)
- Añadimos la rama v0.2 con el comando "git branch v0.2"
- Posicionamos la carpeta en la rama v0.2 con "git checkout v0.2"
- Añadimos el fichero 2.txt a la rama v0.2 con "nano 2.txt"
	**git add 2.txt"
	**git commit -m "Commit 3""
	**git push
	
Ejercicio 9 (Merge directo)
- Posicionamos en la rama main con "git checkout main"
- Hacemos un merge de la rama v0.2 en la rama master con "git merge v0.2 main"

Ejercicio 10 (Merge con conflicto)
En la rama **master** poner **Hola** en el fichero **1.txt** y hacer commit.
- Utilizamos "nano 1.txt" introducimos Hola en el fichero, lo visualizamos con "cat 1.txt".
- Lo subimos con "git add 1.txt", "git commit -m "Commit 5"", "git push"

<<<<<<< HEAD
Posicionarse en la rama **v0.2** y poner **Adios** en el fichero "1.txt" y hacer commit.
=======
Posicionarse en la rama **v0.2** y poner **Adios** en el fichero "1.txt" y hacer commit.
- Nos posicionamos con "git checkout v0.2"
- Editamos fichero con "nano 1.txt"
- Commit con "git commit -m "Commit 6""
- Push con "git push"

Posicionarse de nuevo en la rama **master** y hacer un merge con la rama **v0.2**
- Nos posicionamos con "git checkout main"
- Hacemos merge con "git merge v0.2 main"
>>>>>>> v0.2
