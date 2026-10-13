# Sonora — música libre

PWA estática, en español, para móvil. Consulta Audius e Internet Archive en vivo; no contiene canciones precargadas ni requiere cuenta. Favoritos, preferencias y lista de reproducción se almacenan en localStorage.

## Desarrollo local
Servir este directorio por HTTPS o localhost (requerido para Service Worker). Para GitHub Pages, habilitar Pages con GitHub Actions.

## Importante
Jamendo requiere `client_id`; no se consulta sin una credencial autorizada. La disponibilidad/streaming depende de los permisos y archivos que expone cada catálogo. Importar un CSV busca coincidencias en Audius.
