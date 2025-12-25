# QBCore + CommunityOx txAdmin Recipe

Recipe para desplegar automáticamente un servidor FiveM con **QBCore** y el ecosistema **CommunityOx** (ox_lib, ox_inventory, ox_target, ox_doorlock, oxmysql, etc.), preconfigurado en español (es / es-ES). [web:6][web:117]

## Características

- Instala QBCore base y recursos esenciales. [web:46][web:180]  
- Usa forks de **CommunityOx** para los scripts `ox_` (ox_lib, ox_inventory, ox_target, ox_doorlock, oxmysql). [web:117][web:141]  
- Configuración por defecto en **es-ES** (locale servidor, qb_locale, ox locale). [web:141]  
- Incluye scripts standalone y addons habituales (pma-voice, ps-ui, Renewed-Weathersync, etc.). [web:109]  
- `server.cfg` ya preparado para español y uso de target. [web:155]

## Cómo usar la receta en txAdmin

1. Crea un servidor nuevo en txAdmin y elige **Custom Template / Remote URL**. [web:29][web:58]  
2. Pega esta URL en el campo de receta:

https://raw.githubusercontent.com/Vicomoe/recipe-qb-ox-community/main/recipe.yaml


3. Revisa la lista de tareas y pulsa **Run Recipe**. [web:25]  
4. Introduce tu **License Key** y tus datos de base de datos cuando te lo pida el asistente. [web:22]  
5. Al finalizar, haz clic en **Save & Run Server**.

## Ajustes recomendados tras la instalación

- Edita `server.cfg` para poner:
- `sv_hostname` con el nombre real de tu servidor.  
- `sets website`, `sets 📢Discord`, etc., con tus enlaces. [web:155]  
- `mysql_connection_string` con tus datos reales de MySQL/MariaDB. [web:173]

- Revisa:
- `ox.cfg` para opciones de ox_lib / ox_inventory. [web:141]  
- `voice.cfg` para la configuración de pma-voice.  
- `settings.cfg` y `misc.cfg` para detalles avanzados.

## Estructura del repositorio

- `recipe.yaml` – Receta principal para txAdmin. [web:25]  
- `server.cfg` – Ejemplo de configuración básica adaptada a esta receta. [web:155]  
- `LICENSE` – Licencia MIT. [web:104]  
- `.gitignore` – Archivos a ignorar por Git. [web:66]

---

Cualquier PR o sugerencia de scripts adicionales compatibles con CommunityOx es bienvenida.
