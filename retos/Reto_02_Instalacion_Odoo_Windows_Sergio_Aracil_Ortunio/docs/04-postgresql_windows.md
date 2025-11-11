# 04 — PostgreSQL en Windows

> Odoo requiere **PostgreSQL**. Según instalador y versión, se incluye o puede requerir instalación separada.

 1. Verifica si el instalador de Odoo **instala PostgreSQL** automáticamente.

 ![PostgreSQL incluido](../assets/img/04-postgresql_windows/01_postgresql-incluido.png)
 2. Si no, descarga [**PostgreSQL para Windows**](https://www.postgresql.org/download/windows/) e instálalo:
   - Selecciona versión soportada por tu Odoo (en nuestro caso para Odoo 19 es 13.0 o superior).

   ![PostgreSQL version](../assets/img/04-postgresql_windows/02_postgresql-version.png)
   - Define usuario `postgres` y contraseña **segura** (anótala).
   El usuario está definido como **postgres** por defecto.
   - Daremos a todo **"siguiente"**, y pondremos un contraseña segura (anota ésta y el puerto).

   ![PostgreSQL asistente](../assets/img/04-postgresql_windows/02_porstgresql-asistente.png)
3. Comprueba que el **servicio de PostgreSQL** está en ejecución (puedes hacerlo abriendo **"Servicios"** en Windows).

![Comprobar servicio](../assets/img/04-postgresql_windows/02_comprobar-servicio.png)

> Resultado esperado: PostgreSQL instalado y funcionando (usuario/puerto guardados).