# Johan Pelayo — Portfolio Landing Page

Implementación estática del diseño de Figma proporcionado por Johan: fondo #0b0d12, acentos #9b87f5, tipografías locales Manrope y JetBrains Mono, y retrato original. HTML, CSS y JavaScript sin instalación ni compilación.

## Ver y editar

Abre `index.html` en un navegador, manteniendo la carpeta `assets` a su lado. El sitio no depende de servicios de fuentes ni de enlaces temporales de Figma. Navegación por secciones, menú móvil y diálogo de contacto operativos.

Referencia: https://www.figma.com/design/xs4K8JGVqW5uuTgVzD1j1v/Johan-Pelayo-Portfolio-Landing-Page?node-id=2-116

## Contenido pendiente en el diseño original

El diseño de escritorio incluye proyectos “Próximamente”, descripciones “Lorem ipsum” y testimonios sin nombres reales. El diseño móvil conserva ejemplos distintos. Se adoptó el contenido de escritorio como fuente principal para mantener información coherente en todas las pantallas. Los textos “Lorem ipsum” se sustituyeron por avisos explícitos de contenido pendiente; no se inventaron clientes, testimonios ni resultados.

Antes de compartirlo comercialmente, agrega tus proyectos y testimonios reales. Las tarjetas mantienen su composición original y los espacios violeta de vista previa.

## Contacto

Busca `const CONTACT` al final de `index.html`. Completa `email` y `linkedin` con los datos profesionales que quieras publicar. Vacíos por defecto: no se han publicado datos privados de tu cuenta. El perfil de GitHub enlazado es `johanpelayo`.

Sin correo configurado, el diálogo prepara y copia un mensaje, pero no lo envía. Con un correo válido, habilita “Abrir correo”, que abre el cliente de correo del visitante con un borrador. LinkedIn admite una URL `https://www.linkedin.com/…` o `https://linkedin.com/…`.

## GitHub Pages

Sube todos los archivos, incluida la carpeta `assets`, al repositorio. Si están en la raíz, selecciona Settings → Pages → Deploy from a branch → main → / (root). GitHub mostrará la dirección publicada cuando termine. Si se añaden en `portfolio/` dentro de un repositorio que ya publica desde la raíz, el sitio estará en la subruta `/portfolio/`.

La carpeta del sitio debe conservar la estructura:

- index.html
- .nojekyll
- README.md
- assets/johan-pelayo.jpg
- assets/status.svg
- assets/fonts/*.ttf

Las fuentes se distribuyen bajo SIL Open Font License 1.1; véase `assets/fonts/OFL.txt`.
