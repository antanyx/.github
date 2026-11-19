# .github

- `profile/README.md` — perfil público de la organización.
- `.github/workflows/app-image.yml` — workflow reutilizable: verifica la app, construye la imagen
  en Actions, la publica en GHCR y la despliega por digest (Render en demos, Coolify en producción).

Repo **público** a propósito: así cualquier repo de la org puede usar el workflow. No contiene
ni debe contener secretos.
