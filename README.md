# TechCodeTest

Sitio estático de TechCodeTest: consultoría de software y división móvil. Está construido con HTML y CSS, sin frameworks, sin build, sin JavaScript y sin recursos externos.

## Estructura

```text
/
├── index.html
├── apps/index.html
├── apps/fases-lunares/index.html
├── apps/oraciones/index.html
├── privacy/index.html          # Política de privacidad (ES)
├── privacy/en/index.html       # Privacy Policy (EN)
├── terms/index.html            # Términos de uso (ES)
├── terms/en/index.html         # Terms of Use (EN)
├── assets/styles.css
├── assets/icons/favicon.svg
├── assets/icons/monogram.svg
├── app-ads.txt                 # Marcador de posición para AdMob
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

- **Inicio** (`/`): servicios, división de apps, enfoque y contacto.
- **Apps** (`/apps/`): catálogo de productos propios y páginas de detalle de cada app.
- **Privacidad** (`/privacy/` y `/privacy/en/`): política en español e inglés, con selector de idioma.
- **Términos** (`/terms/` y `/terms/en/`): términos de uso en español e inglés.

El texto de la política de privacidad se basa en el documento original del titular. No edites su contenido legal sin aprobación.

## Notas internas

Términos: revisados por el usuario; no constituyen asesoría legal.

## Publicación

GitHub Pages sirve la raíz de la rama `main`. No hay paso de compilación: los archivos se publican
tal como están. Antes de activar Pages, revisa el cambio y mergea la rama.

Las URLs canónicas, `robots.txt` y `sitemap.xml` usan `https://cedaniel200.github.io/`.

## app-ads.txt

El archivo solo contiene comentarios. Para autorizar inventario de AdMob, pega la línea exacta que
proporciona la consola de AdMob y elimina el marcador de posición. No inventes el publisher ID.

## Contacto

`tech.code.test@gmail.com` · [GitHub](https://github.com/cedaniel200)
