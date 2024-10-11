---
title: Hello World
description: Showcase ideal blog structure
publishDate: 2024-06-24
authors: Vinay Gaykar
draft: false
---


This is an ideal blog.

## Structure & URL

This blog is actually an `index.md` file located under `content/ideal-blog/index.md`.
Everything under `content` directory is published and the directory name becomes the URL slug.
E.g. this page is available at `https://<your-domain>/ideal-blog` because the directory was named `ideal-blog`.

All the other assets related to this blog like images & cover images should also go in the same folder i.e. `ideal-blog`

It is possible to change the slug to ignoring the directory name, see next section.


## Metadata & SEO

It has frontmatter at start of the file which dictates blog's metadata as shown below.

```
title: Hello World <- [Blog title which you see above this page]
description: Showcase ideal blog structure <- [Blog description/introduction]
publishDate: 2024-06-24 <- [Date of publishing]
authors: Vinay Gaykar <- [Author's name]
draft: false <- [Set to "true" and this blog will not be published]
```

Frontmatter data is not only visible on the page but is also used to populate `<meta>` tags of this
web page which are required for SEO.

To use custom slug you can provide the property `slug` in the frontmatter. Suppose of this page 
`slug: random-page` was set then this page would be available at `https://<your domain>/random-page`.


## Cover image

For cover image, just add an image with the name `cover` in same folder as this markdown file.


## Markdown support

To see how to write a blog and supported tags in markdown visit [markdown-support page](/mardown-support).

