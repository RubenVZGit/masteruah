# masteruah
*Repositorio de la practica GIT*

Ejercicio 2
- Clonamos con 
$git clone https://github.com/RubenVZGit/masteruah.git

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

Posicionarse en la rama **v0.2** y poner **Adios** en el fichero "1.txt" y hacer commit.

Posicionarse en la rama **v0.2** y poner **Adios** en el fichero "1.txt" y hacer commit.
- Nos posicionamos con "git checkout v0.2"
- Editamos fichero con "nano 1.txt"
- Commit con "git commit -m "Commit 6""
- Push con "git push"

Posicionarse de nuevo en la rama **master** y hacer un merge con la rama **v0.2**
- Nos posicionamos con "git checkout main"
- Hacemos merge con "git merge v0.2 main"
>>>>>>> v0.2


Ejercicio 11 (Listado de ramas)
Listar ramas con merge "git branch --merged"
Listar ramas con merge "git branch --no-merged"

Ejercicio 12 (Arreglar el conflicto anterior y hacer un commit)
Arreglar con "vim 1.txt"

Ejercicio 13 (Borrar rama v0.2)
Creamos tag v0.2 "git tag v0.2"
Eliminamos la rama v0.2 "git branch -D v0.2"

Ejercicio 14 (Listado de cambios)
Listamos los cambios "git log --oneline --decorate --all"

Ejercicio 15 (Cuenta de GitHub)
- Poner una foto en vuestro perfil de GitHub.
- Poner el doble factor de autentificación en vuestra cuenta de GitHub.
- Añadir (si no lo habéis hecho ya) la clave pública que se corresponde a tu ordenador.

Ejercicio 16 (Uso social de GitHub)
- Preguntar los nombres de usuario de GitHub de tus compañeros de trabajo en grupo, búscalos, y sigueles.
- Añadir una estrella a los repositorios del resto de tus compañeros.

Ejercicio 17 (Crear una tabla)
<table>
	<tr>
	   <th>NOMBRE</th>
	   <th>GITHUB</th>
	</tr>
	<tr>
	   <th>Mleiva04</th>
	   <th>https://github.com/Mleiva04</th>
	</tr>
</table>

Ejercicio 18 (Colaboradores)
- Poner a [github.com/i12vecaj](http://github.com/i12vecaj) como colaborador del repositorio **masteruah**

Ejercicio 19 (Crear una organización)
- Crear una organización llamada **masteruah-tunombredeusuariodegithub**

Ejercicio 20 (Crear equipos)
- Crear 2 equipos en la organización **masteruah-tunombredeusuariodegithub**, uno llamado **administradores** con más permisos y otro **colaboradores** con menos permisos.
- Meter a [github.com/i12vecaj](http://github.com/i12vecaj) y a 2 de vuestros compañeros de clase en el equipo **administradores**.
- Meter a [github.com/i12vecaj](http://github.com/i12vecaj) y a otros 2 de vuestros compañeros de clase en el equipo **colaboradores**.

Ejercicio 21 (Crear index)
- Crear un index.html que se pueda ver como página web en la organización.

Ejercicio 22 (Crear Pull-requests)
- Hacer 2 forks de 2 repositorios **masteruah-tunombredeusuariodegithub.github.io** de 2 organizaciones de las que no seais ni administradiores ni colaboradores.
- Crearos una rama en cada fork.
- En cada rama modificar el fichero **index.html** añadiendo vuestro nombre.
- Con cada rama hacer un pull-request.

Ejercicio 23 (Gestionar Pull-requests)
- Aceptar los pull-request que lleguen a los repositorios de tu organización.
