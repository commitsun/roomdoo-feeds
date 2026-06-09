# roomdoo-feeds

Feeds RSS **públicos** de las novedades de Roomdoo, servidos por GitHub Pages
para que el dashboard (módulo Odoo `feed_rss`) los consuma.

- `news.xml`    — novedades en español (es-ES)
- `news-en.xml` — changelog en inglés (en-US, fallback universal)

## ⚠️ No editar a mano

Estos archivos se **generan automáticamente** desde `commitsun/roomdoo-docs`
(`es/novedades.mdx` y `en/changelog.mdx`) y un workflow los empuja aquí en cada
cambio. Cualquier edición manual se sobrescribirá.

URLs públicas (vía GitHub Pages):

- https://commitsun.github.io/roomdoo-feeds/news.xml
- https://commitsun.github.io/roomdoo-feeds/news-en.xml
