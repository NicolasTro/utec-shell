# Shell, permissions

Este directorio contiene scripts de Bash para aprender sobre permisos, usuarios y grupos en sistemas tipo Unix.

## Descripción de los scripts

- `0-iam_betty`: Cambia el usuario actual al usuario `betty`.
- `1-who_am_i`: Imprime el nombre del usuario actual (usuario efectivo).
- `2-groups`: Imprime todos los grupos a los que pertenece el usuario actual.
- `3-new_owner`: Cambia el propietario del archivo `hello` al usuario `betty`.
- `4-empty`: Crea un archivo vacío llamado `hello`.
- `5-execute`: Agrega permiso de ejecución al usuario propietario del archivo `hello`.
- `6-multiple_permissions`: Agrega permisos de ejecución al dueño y al grupo, y permiso de lectura a otros usuarios, para el archivo `hello`.
- `7-everybody`: Agrega permiso de ejecución a todos (dueño, grupo y otros) para el archivo `hello`.
- `8-James_Bond`: Establece permisos para que únicamente otros usuarios tengan todos los permisos (lectura, escritura y ejecución) sobre el archivo `hello`.
- `9-John_Doe`: Establece el modo de permisos `753` (`rwxr-x-wx`) para el archivo `hello`.
- `10-mirror_permissions`: Copia y aplica el modo de permisos del archivo `olleh` al archivo `hello`.
- `11-directories_permissions`: Agrega permisos de ejecución a todos los subdirectorios del directorio actual.
- `12-directory_permissions`: Crea un directorio llamado `my_dir` con permisos `751` (`rwxr-x--x`).
- `13-change_group`: Cambia el grupo propietario del archivo `hello` a `school`.
- `14-change_owner_and_group`: Cambia el propietario a `vincent` y el grupo a `staff` para todos los archivos y directorios del directorio actual.
- `15-symbolic_link_permissions`: Cambia el propietario a `vincent` y el grupo a `staff` del enlace simbólico `_hello`.
- `16-if_only`: Cambia el propietario del archivo `hello` a `vincent` solo si actualmente pertenece a `guillaume`.
