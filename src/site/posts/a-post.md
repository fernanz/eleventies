---
title: Un nuevo despertar
description: Esta parte contiene una línea de texto que describe brevemente el contenido del post.
date: 2023-12-15
---

![Imagen de ejemplo](https://res.cloudinary.com/magnvs/image/upload/v1702957059/2024-assets/IMG_0861.jpg)

There's not much here in the sample post page. Better get to work.

The common front-matter data for all of the files in the posts section are abstracted into a `posts.json` file so that we don't need to repeat that on every file. Handy.

It looks like this:

```js
{
  "layout" : "layouts/post.md",
  "tags" : "post",
  "templateEngineOverride": "njk,md"
}
```


