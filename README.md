# Actualizaciones

Este repo solo publica los APK de las apps (en **Releases**) y `update.json`, que las apps
consultan para ofrecer la versión nueva. El código fuente no está aquí.

`update.json`:

- `apps.<app>`: última versión de cada app (`versionCode`, `versionName`, `apk`, `sha256`, `notes`).
- `domains`: cambios de dominio que las apps aplican sin reinstalar, por ejemplo
  `{"sitio-viejo.com": "sitio-nuevo.com"}`.
