# memori-legal

Documentos legales públicos de **Memori** (política de privacidad, términos de servicio), alojados con GitHub Pages para cumplir el requisito de Google Play Store de una política de privacidad accesible públicamente.

Ver `memoriapp/docs/08-privacy-policy.md` en el repo principal para el proceso completo.

## Contenido

- `docs/index.html` — página principal con enlaces
- `docs/privacy-policy.html` — política de privacidad (versión v1.0: local-first, sin cuenta)
- `docs/terms-of-service.html` — términos de servicio

## Publicar

1. Push a `main`
2. En **Settings → Pages**: Source = `main` / `/docs`
3. URL resultante: `https://jaimetellezb.github.io/memori-legal/`

## Actualizar

Al llegar v1.1 (cuenta + sync opcional), hay que:
- reactivar las secciones `[v1.1]` en `privacy-policy.html` (ver el template completo en `docs/08-privacy-policy.md` del repo principal)
- agregar `docs/account-deletion.html` (obligatoria en Play Data Safety para apps con cuentas)
- enlazar `account-deletion.html` desde `index.html`
