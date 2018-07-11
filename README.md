# library.nyu.edu-style_guide
library.nyu.edu Style Guide

[Live site](//nyulibraries.github.io/library.nyu.edu-style_guide/)


# Editing Guide

Contributions are availabe publically via [prose.io](https://prose.io/#NYULibraries/library.nyu.edu-style_guide)

## Add guides:
* `Create new file` with a `.markdown` extension and write in a combination of HTML and Markdown.
* The page will automatically be added to the front-page list of guides.

## Layouts & Frontmatter

The default layout is `guide`, which will render a `Preview` and `Code Example` of the content.
The `article` layout will exclude these sections and simply render the content.
Switch the `markdown` flag to `true` to use markdown page (the file extension can still be HTML).

```yml
---
title: Typography
layout: article # Excludes 'preview' and 'code example' sections in guides (default: guide)
---
```
