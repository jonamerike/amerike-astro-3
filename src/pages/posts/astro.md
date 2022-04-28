---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Comandos de Astro
publishDate: 28 Abr 2022
name: Jon MirCha
value: 128
description: Un resumen de los apuntes de Git
---

<Cool name={frontmatter.name} href="https://twitter.com/jonmircha" client:load />

### Astro

[Sitio Oficial](https://astro.build/)

#### Instalación

```bash
mkdir carpeta-proyecto
cd carpeta-proyecto
npm create astro@latest
# en el asistente de instalación escribir:
#   y
#   .
#   elegir un template
npm install
```

#### Comenzar la aplicación en local

```bash
npm start
```

#### Construir el sitio para producción

```bash
npm run build
```
