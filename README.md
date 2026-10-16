# Tribu de Sinvergüenzas — web estática

Reconstrucción estática de https://jefe468.wixsite.com/website (Wix) para alojarla
gratis en GitHub Pages. Cinco páginas, sin dependencias ni compilación:

- `index.html` — portada con los cuatro juegos
- `tribufamiliar.html`, `tribu.html`, `wasa.html`, `sigamospecando.html`
- `css/style.css` — hoja de estilos común
- `images/` — todas las imágenes, descargadas del CDN de Wix (ya no se enlaza nada a Wix)

## Notas

- Tipografías: Anton, Suez One y Poppins son las mismas que usaba el original;
  Futura → Jost, Avenir/Museo/Proxima → Nunito Sans, Rosewood → Rye (Google Fonts).
- Los botones de compra conservan las URLs de Amazon originales, incluidas las
  etiquetas de Amazon Attribution (`maas`).
- La portada original no tenía enlace de vuelta a sí misma; se ha añadido "INICIO".
- El muro de Instagram del original era un componente de Wix: aquí se sustituye por
  un enlace al perfil.
- Los precios están escritos en el HTML; hay que actualizarlos si cambian en Amazon.
