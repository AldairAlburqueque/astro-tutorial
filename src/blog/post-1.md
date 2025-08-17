---
# layout: ../../layouts/MarkdownPostLayout.astro
title: "Mi primera publicación en el blog"
pubDate: 2022-07-01
description: "Este es la primera publicación de mi nuevo blog Astro."
author: "Alumno de Astro"
image:
  url: "https://docs.astro.build/assets/full-logo-light.png"
  alt: "El logotipo completo de Astro."
tags: ["astro", "bloguear", "comunidad"]
---

<!-- # Mi primera publicación en el blog -->

<!-- Publicado el: 2022-07-01 -->

¡Bienvenido a mi _nuevo blog_ sobre el aprendizaje de Astro! Aquí, voy a compartir mi viaje de aprendizaje a medida que construyo un nuevo sitio web.

## Lo que he conseguido

1. **Instalación de Astro**: En primer lugar, he creado un nuevo proyecto Astro y configurar mis cuentas en línea.

2. **Creación de páginas**: Luego aprendí cómo hacer páginas creando nuevos archivos `.astro` y colocándolos en la carpeta `src/pages/`.

3. **Creación de publicaciones**: ¡Esta es mi primera publicación! ¡Ahora tengo páginas de Astro y publicaciónes en Markdown!

## Próximos pasos

Terminaré el tutorial de Astro, y luego seguiré añadiendo más publicaciones. Mira este espacio para más por venir.

Comprueba de nuevo la vista previa de tu navegador en http://localhost:4321/posts/post-1. Ahora deberías ver el contenido de esta página. Puede que aún no esté formateado correctamente, ¡pero no te preocupes, lo actualizarás más tarde en el tutorial!

Utiliza las herramientas de desarrollo de tu navegador para inspeccionar esta página. Observa que, aunque no has escrito ningún elemento HTML, tu Markdown se ha convertido a HTML. Puedes ver elementos como encabezados, párrafos y elementos de lista.

Nota

La información en la parte superior del archivo, dentro de las vallas de código, se llama frontmatter. Estos datos -incluyendo etiquetas y una imagen de la publicación- son información sobre tu publicación que Astro puede usar. No aparece en la página automáticamente, pero accederás a ella más adelante en el tutorial para mejorar tu sitio.

Enlaza tus publicaciones
Enlaza a tu primera publicación con una etiqueta anchor en src/pages/blog.astro:

## src/pages/blog.astro

---

<html lang="es">
  <head>
    <meta charset="utf-8"/>
    <meta name="viewport" content="width=device-width" />
    <title>Astro</title>
  </head>
  <body>
    <a href="/">Inicio</a>
    <a href="/about/">Sobre mi</a>
    <a href="/blog/">Blog</a>

    <h1>Mi blog de aprendizaje sobre Astro</h1>
    <p>Aquí es donde publicaré acerca de mi viaje aprendiendo Astro./p>
    <ul>
      <li><a href="/posts/post-1/">Publicación 1</a></li>
    </ul>

  </body>
</html>

Ahora, añade dos ficheros más en src/pages/posts/: post-2.md y post-3.md. Aquí tienes un ejemplo de código que puedes copiar y pegar en tus archivos, ¡o puedes crear el tuyo propio!

## src/pages/posts/post-2.md

title: Mi segunda publicación en el blog
author: Alumno de Astro
description: "Después de aprender un poco de Astro, ¡no podía parar!"
image:
url: "https://docs.astro.build/assets/arc.webp"
alt: "Miniatura de los arcos de Astro."
pubDate: 2022-07-08
tags: ["astro", "bloguear", "aprender en público", "éxitos"]

---

Después de una exitosa primera semana aprendiendo Astro, decidí probar un poco más. Escribí e importé un pequeño componente de memoria.

## src/pages/posts/post-3.md

title: Mi tercera publicación en el blog
author: Alumno de Astro
description: "Tuve algunos problemas, pero preguntar en la comunidad me ayudó mucho."
image:
url: "https://docs.astro.build/assets/rays.webp"
alt: "Miniatura de los rayos de Astro."
pubDate: 2022-07-15
tags: ["astro", "aprender en público", "contratiempos", "comunidad"]

---

No siempre ha sido fácil, pero disfruto construyendo con Astro. Además, la [comunidad de Discord](https://astro.build/chat) es muy amable
