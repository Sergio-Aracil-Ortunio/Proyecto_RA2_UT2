# 04 — PostgreSQL en Linux

1. Instala PostgreSQL desde repos:
   ```bash
   sudo apt install postgresql
   ```
   ![Instalar PostgreSQL](../assets/img/04-postgresql_linux/01_instalar-postgresql.png)
2. Verifica el servicio:
   ```bash
   sudo systemctl status postgresql
   ```
   ![Servicio PostgreSQL](../assets/img/04-postgresql_linux/02_status-postgresql.png)

3. (Opcional) Cambia contraseña del usuario `postgres` o crea rol específico para Odoo.

   Cambia la contraseña con (**IMPOTANTE** Reinicia el servicio tras loc cambios para aplicarlos):
   ```bash
   sudo -u postgres psql -c "ALTER USER postgres WITH PASSWORD 'nueva_contraseña';"
   ```
   ![Cambiar contraseña](../assets/img/04-postgresql_linux/03_cambiar_contrasenia.png)

- [ ] PostgreSQL instalado
- [ ] Servicio Activo
