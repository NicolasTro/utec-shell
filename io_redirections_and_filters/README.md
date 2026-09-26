# Shell, I/O Redirections and Filters

Este directorio contiene scripts de Bash para aprender sobre redirecciones de entrada/salida (I/O) y filtros en sistemas tipo Unix.

## Descripción de los scripts

- `0-hello_world`: Imprime en pantalla "Hello, World" seguido de un salto de línea.
- `1-confused_smiley`: Muestra en pantalla la carita sonriente confundida `"(Ôo)'`.
- `2-hellofile`: Muestra el contenido del archivo `/etc/passwd`.
- `3-twofiles`: Muestra el contenido de los archivos `/etc/passwd` y `/etc/hosts`.
- `4-lastlines`: Muestra las últimas 10 líneas del archivo `/etc/passwd`.
- `5-firstlines`: Muestra las primeras 10 líneas del archivo `/etc/passwd`.
- `6-third_line`: Muestra la tercera línea del archivo `iacta`.
- `7-file`: Crea un archivo llamado exactamente `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` conteniendo el texto `Best School`.
- `8-cwd_state`: Escribe el resultado del comando `ls -la` en el archivo `ls_cwd_content`.
- `9-duplicate_last_line`: Duplica la última línea del archivo `iacta`.
- `10-no_more_js`: Elimina todos los archivos con extensión `.js` en el directorio actual y subdirectorios.
- `11-directories`: Cuenta el número de directorios y subdirectorios en el directorio actual.
- `12-newest_files`: Muestra los 10 archivos más nuevos del directorio actual, uno por línea, ordenados del más reciente al más antiguo.
- `13-unique`: Toma una lista de palabras como entrada e imprime únicamente las que aparecen exactamente una vez.
- `14-findthatword`: Muestra las líneas que contienen el patrón "root" en el archivo `/etc/passwd`.
- `15-countthatword`: Muestra el número de líneas que contienen el patrón "bin" en el archivo `/etc/passwd`.
- `16-whatsnext`: Muestra las líneas que contienen el patrón "root" y las 3 líneas siguientes a cada coincidencia en `/etc/passwd`.
- `17-hidethisword`: Muestra todas las líneas del archivo `/etc/passwd` que no contienen el patrón "bin".
- `18-letteronly`: Muestra todas las líneas del archivo `/etc/ssh/sshd_config` que comienzan con una letra.
- `19-AZ`: Reemplaza todas las apariciones de los caracteres `A` y `c` por `Z` y `e` respectivamente.
- `20-hiago`: Elimina todas las letras `c` y `C` de la entrada estándar.
- `21-reverse`: Invierte la entrada estándar recibida.
- `22-users_and_homes`: Muestra todos los usuarios y sus directorios personales contenidos en `/etc/passwd`, ordenados alfabéticamente por usuario.
