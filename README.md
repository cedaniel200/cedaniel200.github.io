# TechCodeTest

Sitio estático de TechCodeTest: consultoría de software y productos propios. HTML y CSS, sin
frameworks, sin build, sin dependencias y sin recursos externos. Tiene un único script en línea de
483 B, limitado al tema: recuerda la elección, la aplica antes del primer pintado y actualiza
`theme-color`. El sitio funciona sin JavaScript. El script se inicializa en `window.onload`; ninguna otra parte de la página usa ese manejador.

## Estructura

```text
/
├── 404.html
├── index.html
├── apps/index.html
├── apps/fases-lunares/index.html
├── apps/oraciones/index.html
├── privacy/index.html          # Política de privacidad (ES)
├── privacy/en/index.html       # Privacy Policy (EN)
├── terms/index.html            # Términos de uso (ES)
├── terms/en/index.html         # Terms of Use (EN)
├── assets/og-image.png
├── assets/styles.css
├── assets/icons/apple-touch-icon.png
├── assets/icons/favicon.svg
├── assets/icons/favicon-dark.svg
├── app-ads.txt                 # Línea de autorización de AdMob
├── favicon.ico
├── robots.txt
├── sitemap.xml
└── README.md
```

## Vista local

Desde la raíz del repositorio:

```bash
python3 -m http.server 8000
```

Abre <http://localhost:8000>. No hace falta instalar nada.

## Contenido

- **Inicio** (`/`): hero de consultoría, servicios, método, trayectoria, productos propios, primer
  paso y contacto.
- **Apps** (`/apps/`): registro de productos propios y fichas textuales de cada app.
- **Privacidad** (`/privacy/` y `/privacy/en/`): política en español e inglés, con selector de idioma.
- **Términos** (`/terms/` y `/terms/en/`): términos de uso en español e inglés.

El texto de la política de privacidad se basa en el documento original del titular. No edites su
contenido legal sin aprobación.

## Notas internas

Términos: revisados por el usuario; no constituyen asesoría legal.

## Publicación

El sitio se publica desde la raíz de la rama `main` como sitio estático. No hay paso de compilación:
los archivos se publican tal como están. Antes de publicar, revisa el cambio y mergea la rama.

Las URLs canónicas, `robots.txt` y `sitemap.xml` usan el dominio público del sitio.

## app-ads.txt

Contiene la línea de autorización de AdMob del titular. No la edites ni inventes el publisher ID.

## Contacto

`tech.code.test@gmail.com`
