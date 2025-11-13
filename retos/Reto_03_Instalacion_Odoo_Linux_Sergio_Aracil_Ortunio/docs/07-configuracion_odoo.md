# 07 — Configuración de Odoo (`/etc/odoo/odoo.conf`)

1. Crea/edita el archivo de configuración con:
   ```bash
   sudo nano /etc/odoo/odoo.conf
   ```
   ```ini
   [options]
   ; This is the password that allows database operations:
   ; admin_passwd = admin
   db_host = False
   db_port = False
   db_user = odoo
   db_password = False
   ;addons_path = /usr/lib/python3/dist-packages/odoo/addons
   default_productivity_apps = True
   ```
2. Crea carpetas y permisos si procede:
   ```bash
   sudo mkdir -p /var/log/odoo && sudo chown odoo:odoo /var/log/odoo
   ```

- [ ]Configuración mínima funcional creada.
