*Comandos comunes de Git*

Uso: git [-v | --version] [-h | --help] [-C <ruta>] [-c <nombre>=<valor>]
[--exec-path[=<ruta>]] [--html-path] [--man-path] [--info-path]
[-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy-fetch]
[--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
[--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envvar>]
<command> [<args>]

**Estos son comandos Git comunes que se usan en varias situaciones:**

*iniciar* un área de trabajo (ver también: tutorial de ayuda de git)
*clone* Clonar un repositorio en un nuevo directorio
*init* Crear un repositorio Git vacío o reinicializar uno existente

trabajar en el cambio actual (ver también: ayuda de git todos los días)
*add* Agregar contenido de archivo al índice
*mv* Mover o renombrar un archivo, un directorio o un enlace simbólico
*restore* Restaurar archivos del árbol de trabajo
*rm* Eliminar archivos del árbol de trabajo y del índice

examinar el historial y estado (ver también: git help revisions)
*bisect* Utilizar la búsqueda binaria para encontrar el commit que introdujo un error
*diff* Mostrar cambios entre commits, commit y árbol de trabajo, etc.
*grep* Imprimir líneas que coinciden con un patrón
*log* Mostrar registros de commits
*show* Mostrar varios tipos de objetos
*status* Mostrar el estado del árbol de trabajo

grow, marcar y ajustar su historial común
*backfill* Descargar objetos faltantes en un clon parcial
*branch* Enumerar, crear o eliminar ramas
*commit* Registrar cambios en el repositorio
*merge* Unir dos o más historiales de desarrollo
*rebase* Reaplicar commits sobre otra base tip
*reset* Restablecer HEAD actual al estado especificado
*switch* Cambiar rama