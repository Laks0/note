# NOTE

Un script para organizar y tomar notas.  

El script usa el editor predeterminado del sistema.

### Dependencias opcionales
- fzf (puede ser reemplazado por otro programa, o no usar el selector por defecto del script)

### Instrucciones básicas
'note [NOMBRE DE LA NOTA]' Crea una nueva nota con el nombre "yy-mm-dd NOMBRE DE LA NOTA" (donde yy-mm-dd es la fecha)
'note -o' Abre un selector de las notas creadas para editar.
'note -l' Muestra una lista de las notas creadas.
'note -r' Abre un selector de las notas creadas para eliminar.
'note -p [NOMBRE DE LA NOTA]' Crea una nueva nota sin poner la fecha en el nombre del archivo.  

Por defecto las notas se guardan en ~/Documents/notas aunque se puede cambiar editando el script.
