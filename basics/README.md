# basics

Scripts del proyecto Shell, basics.

## Scripts

- **0-current_working_directory** — Imprime la ruta absoluta del directorio de trabajo actual (pwd).
- **1-listit** — Muestra el listado del contenido del directorio de trabajo actual (ls).
- **2-bring_me_home** — Cambia el directorio de trabajo al directorio home del usuario (cd sin argumentos; usar con source para afectar la shell actual).
- **3-listfiles** — Lista el contenido del directorio actual en formato largo (ls -l).
- **4-listmorefiles** — Lista todo el contenido, incluidos archivos ocultos, en formato largo (ls -la).
- **5-listfilesdigitonly** — Lista en formato largo, UID/GID numéricos y archivos ocultos (ls -na).
- **6-firstdirectory** — Crea el directorio /tmp/my_first_directory.
- **7-movethatfile** — Mueve /tmp/betty a /tmp/my_first_directory.
- **8-firstdelete** — Elimina el archivo /tmp/my_first_directory/betty.
- **9-firstdirdeletion** — Elimina el directorio vacío /tmp/my_first_directory.
- **10-back** — Cambia al directorio de trabajo anterior (cd -; usar con source).
- **11-lists** — Lista en formato largo y con ocultos el directorio actual, el padre y /boot (ls -al . .. /boot).
- **12-file_type** — Muestra el tipo del archivo /tmp/iamafile (file).
- **13-symbolic_link** — Crea el enlace simbólico __ls__ apuntando a /bin/ls en el cwd (ln -s).
- **14-copy_html** — Copia los .html del cwd al directorio padre solo si no existen allí o el origen es más reciente (cp -u).
- **15-lets_move** — Mueve al directorio /tmp/u los archivos cuyo nombre empieza por mayúscula (mv [[:upper:]]*).
- **17-tree** — Crea welcome/, welcome/to/ y welcome/to/school con mkdir -p (script con solo dos espacios en total).
