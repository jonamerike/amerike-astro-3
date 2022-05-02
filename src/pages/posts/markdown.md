---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Sintaxis Markdown
publishDate: 02 May 2022
name: Jon MirCha
value: 128
description: Un resumen de la sintaxis Markdown
---

<Cool name={frontmatter.name} href="https://twitter.com/jonmircha" client:load />

_Markdown_ es un lenguaje de marcado ligero creado en 2004 por _John Gruber_, trata de conseguir la máxima legibilidad y facilidad de publicación tanto en su forma de entrada como de salida, inspirándose en muchas convenciones existentes para marcar mensajes de correo electrónico usando texto plano.

Facilita la aplicación de formato y estilo a texto plano empleando una serie de caracteres de forma especial.

El objetivo de su creador fue hacer que la gente pudiera escribir usando un formato de texto plano fácil de leer, fácil de escribir y con la posibilidad de convertir su documento en _HTML_ válido.

La gran simpleza de su sintaxis hizo que tuviera una rápida adopción y popularidad en la comunidad de desarrolladores.

Actualmente aparte de permitir generar contenido _HTML_ de forma dinámica, también se emplea (casí de forma estándar) para la creación de documentación técnica y con la proliferación de la arquitectura _JAM Stack_ para la creación de sitios estáticos a través de herramientas de tipo _SSG_ (_Static Site Generator_) y _SSR_ (_Server Side Rendering_) como _Hugo_, _Gatsby_, _Eleventy_, _Next.js_, _Sergey_, _Astro_, entre otros, _Markdown_ se ocupa para la generación de contenido editorial (artículos de _blog_) de forma dinámica.
