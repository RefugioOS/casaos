# 2FAuth - CasaOS

<!-- PORT-VERSION-BEGIN -->
Version: `8.0.2-refugioos.1` - ficha neutral apps/2fauth/app.yaml
<!-- PORT-VERSION-END -->

Port de RefugioOS para CasaOS.

- Imagen: ghcr.io/refugioos/2fauth:8.0.2-refugioos.1 (amd64 + arm64), versionada, nunca `latest`.
- Interfaz web: http://localhost:3482
- "Gestor web de doble factor: TOTP/HOTP, WebAuthn y generacion de codigos."

Para actualizar: `python publicar-casaos.py --app 2fauth --mode update`
(o regenera la salida con `--mode update --version <nuevo-tag> --force`).

Nota: la instalacion real en CasaOS se hace desde el App Store apuntando a
este repositorio (estructura Apps/<AppName>/ con docker-compose.yml + icon.png).
