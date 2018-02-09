### Zonas de Git
`1.- Directorio de trabajo
2.- Area de preparación
3.- Directorio Git`

### Flujo de trabajo basico en Git
git config --global user.name "atareao"
git config --global user.email atareao@atareao.es
git config --global core.editor sublime_text.exe
mkdir ejemplo00 (Agregar carpeta)
cd ejemplo00 (abrir carpeta)
git ini (inicializar repositorio)

add readme.md (stating area)

git status (estatus del repositorio)

git commit -m "Comit inicial" (confirmar .git repositorio )

git log (historial de confirmaciones commit archivos del rpositorio)

git diff (diferencia de archivos).

git diff --staged (ver la dirferencia entre lo que ya preparamos y lo que aun no preparamos)

git add . (agregar todos los archivos esten en seguimiento o no a la zona de preparacion)

 git reset HEAD readme.md (sacar archivo de la zona de preparacion)

 git add -A (Guarda todos los archivos que estamos siguiendo con git)

 git commit --amend (modificar el commit)

 .gitignore (ignorar archivos)

 git commit -a -m (saltas zona de preparacion solo para archivos que ya estamos ratreando que ya han tenido un commit)

 git rm (elimina archivo ratreados del repositorio elimina del directorio de trabajo)
se debe confirmar con commit una eliminacion.

 git checkout -- Clase1/definicion.html
 (recuperar archivos borrados de sublime)

 git mv readme.md README.md (renombrar archivos)

clonar, git clone https://github.com/escueladigital/EDgrid.git

clonar con nuevo nombre, git clone https://github.com/escueladigital/EDgrid.git mi-propio-grid

git tag ver todas las etiquetas

etiqueta ligera git tag mi-etiqueta

etiqueta anotada git tag -a v1.0 -m "Mi version 1.0"

git show mi-etiqueta (muestra la info de la etiqutea)

esta liena se creo en la rama master
