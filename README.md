Readme.md
--------------------

En este proyecto podrás practicar:
Realizar un Fork (bifurcación) del proyecto original (upstream).
Generar un Pull Request (petición de incorporación del fork)
Titulo: Realiza un Fork a este repositorio
Para realizar la bifurcación, haz clic en el botón Fork (que se encuentra en la parte superior de esta página), ver imagen:
IMG (gh-fork)
Con esto crearas una copia del proyecto en tu propia cuenta.
Titulo: Clona tu repositorio
Ahora deberás clonar el repositorio que se encuentra en tu cuenta, haz clic en el botón verde “Code” y luego copia el url que aparece ahí.
IMG (gh-clone)
Abre la terminal y ejecuta lo siguiente:
git clone “url copiada”
Titulo: Realiza una contribución
Cuando ya tengas clonado el repositorio en tu computadora, edita el archivo “contribuidores.txt” ingresando ‘tu nombre’ seguido de ‘@tu usuario de twitter’, seguido de “tu frase favorita”.
Ej: 
Melissa @piratelicorne “un día sin sonreir es un dia perdido”
Luego de ingresar la línea de contribución, recuerda actualizar el archivo en tu repositorio:
git status
git add contribuidores.txt
git commit -m “tu_nombre ha contribuido ahora, ya conoce Git”
git push
IMG (gh-contrib)
