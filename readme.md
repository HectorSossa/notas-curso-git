## Curso Git desde Cero
Sistema de control de versiones para el mantto eficiente y confiable de aarchivos.

### Zonas de Git
1.- Directorio de trabajo
2.- Area de preparación
3.- Directorio Git

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