# residuos-cat-landing

Landing pública del producto **leads de residuos B2B Cataluña**.

Estática (HTML + CSS), sirve desde Cloudflare Pages en `leads.vivironline.es`.

## Privacidad

⚠️ Subdominio interno. Triple capa `noindex`:
- Meta `robots` en HTML
- `robots.txt` con `Disallow: /` para todos los crawlers
- Header `X-Robots-Tag` definido en `_headers` (sintaxis Cloudflare Pages)

## Despliegue

Connectado a Cloudflare Pages → cualquier push a `main` se publica automáticamente.

## Contacto

Yoel Castaño — yoelcp1988@gmail.com
