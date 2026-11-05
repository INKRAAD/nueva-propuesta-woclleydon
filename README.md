# Nueva propuesta Woclleydon

Copia visual estática del sitio [Wocl Leydon Español](https://xn--woclleydonespaol-kub.com/) (Wocl Leydon, abogados de accidentes en Connecticut). Sirve como base de propuesta: el diseño, las imágenes, tipografías y enlaces de navegación se conservan lo más fiel posible.

No incluye backend. Los formularios se muestran pero no envían datos.

## Cómo verlo en local

```bash
python3 -m http.server 8080
```

Abre `http://localhost:8080/`.

## Páginas incluidas

| Ruta | Contenido |
| --- | --- |
| `/` | Inicio (landing principal, menú con anclas a secciones) |
| `/post/` | 3 razones para un abogado de lesiones personales en CT |
| `/post2/` | 5 estrategias para maximizar la indemnización por daños a la propiedad |
| `/post3/` | 12 cosas sobre la indemnización por lesiones personales en CT |
| `/post4/` | 15 cosas que hacer después de un accidente |
| `/wl-te-lleva-al-mundial-de-clubes-de-la-fifa/` | Campaña WL te lleva al Mundial de Clubes |
| `/gracias/` | Página de agradecimiento post-formulario |
| `/elementor-8/` | Página histórica presente en el sitemap |

Los assets (imágenes, video, CSS, JS, fuentes Poppins de Elementor) están descargados en `wp-content/` y `wp-includes/`.

## Qué no se clonó o cambia

- Envío de formularios WPForms (visual únicamente; el envío está desactivado).
- Google Tag Manager, Pixel de Facebook / PixelYourSite y llamadas a `wp-json` / `xmlrpc.php`.
- Archivos RSS (`/feed/`) y páginas de autor.
- Widgets que dependen de APIs en vivo (reseñas de Google pueden verse un poco distintas si el script original pide datos remotos).
- Mapas de Google/Apple y redes sociales siguen apuntando a los enlaces externos originales.
