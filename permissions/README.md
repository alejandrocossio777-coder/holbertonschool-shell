# Shell, permissions

Scripts de Bash para el proyecto **Shell, permissions** (Holberton School), Ubuntu 22.04 LTS.

## Scripts

- **0-iam_betty** — Cambia al usuario betty (su betty; 8 caracteres en el comando + newline).
- **1-who_am_i** — Imprime el usuario efectivo (whoami).
- **2-groups** — Imprime los grupos del usuario actual (groups).
- **3-new_owner** — Propietario de hello → betty (chown betty hello); a menudo con sudo.
- **4-empty** — Crea el archivo vacío hello (touch hello).
- **5-execute** — Permisos de hello a 744 (chmod 744 hello).
- **6-multiple_permissions** — Permisos de hello a 754 (chmod 754 hello).
- **7-everybody** — Ejecución para todos (chmod a+x hello).
- **8-James_Bond** — Permisos 007 solo para otros (chmod 007 hello).
- **9-John_Doe** — Permisos 753 (chmod 753 hello).
- **10-mirror_permissions** — Iguala permisos de hello a los de olleh (chmod --reference=olleh hello).
- **11-directories_permissions** — Ejecución en directorios bajo el cwd, recursivo (chmod -R a+X .).
- **12-directory_permissions** — Crea my_dir con modo 751 (mkdir -m 751 my_dir).
- **13-change_group** — Grupo de hello → school (chgrp school hello).
- **14-change_owner_and_group** — Propietario y grupo vincent:staff en todos los archivos del cwd (chown vincent:staff *).
- **15-symbolic_link_permissions** — Cambia dueño del enlace _hello, no del destino (chown -h vincent:staff _hello).
- **16-if_only** — Si hello es de guillaume, pasa a vincent (chown --from=guillaume vincent hello).
