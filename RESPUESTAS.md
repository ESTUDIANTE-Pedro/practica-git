# RESPUESTAS

## (a) git restore vs git revert
- `git restore`: descarta cambios en archivos.
- `git revert`: crea un commit que deshace otro anterior.

## (b) ¿Por qué password.txt sigue siendo un problema?
Porque sigue en el historial de Git y su contenido puede recuperarse, aunque ya no aparezca en la última versión. Si contiene contraseñas reales, hay que cambiarlas.

## (c) git rm vs git rm --cached
- `git rm`: elimina el archivo de Git y del equipo.
- `git rm --cached`: deja de seguirlo en Git, pero lo conserva en el equipo.