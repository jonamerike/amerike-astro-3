---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Hola Mundo!
publishDate: 28 Abr 2022
name: Jon MirCha
value: 128
description: Hola Mundo!
---

<Cool name={frontmatter.name} href="https://twitter.com/jonmircha" client:load />

This is so cool!

Do variables work {frontmatter.value \* 2}?

```javascript
// Example JavaScript

const x = 7;
function returnSeven() {
  return x;
}
```
