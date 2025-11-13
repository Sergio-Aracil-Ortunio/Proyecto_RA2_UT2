# 06 — Instalación de Odoo

## Paquete oficial (repositorio Odoo)
1. Añade repositorio/clave y luego instala `odoo`:
   ```bash
   # (Ejemplo orientativo — ajusta a la versión que uses)
   wget -q -O - https://nightly.odoo.com/odoo.key | 
   sudo gpg --dearmor -o /usr/share/keyrings/odoo-archive-keyring.gpg
   echo "deb [signed-by=/usr/share/keyrings/odoo-archive-keyring.gpg] https://nightly.odoo.com/19.0/nightly/deb/ ./" | 
   sudo tee /etc/apt/sources.list.d/odoo.list
   sudo apt-get update && sudo apt-get install odoo
   ```
   ![Añadir repositorio](../assets/img/06-instalacion_odoo/01_aniadir-repositorio.png)

2. Crea usuario odoo:
   ```bash
   sudo adduser --system --home=/opt/odoo --gorup odoo
   ```
   ![Crear usuario odoo](../assets/img/06-instalacion_odoo/02_crear-usuario-odoo.png)

- [ ] Binarios/código de Odoo instalados.
