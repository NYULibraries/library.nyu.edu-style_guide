# library.nyu.edu-style_guide
library.nyu.edu Style Guide

[Live site](//nyulibraries.github.io/library.nyu.edu-style_guide/)


# Editing Guide

Contributions are availabe publically via [prose.io](https://prose.io/#NYULibraries/library.nyu.edu-style_guide)

## Frontpage

Main `index.html` editable [here](https://github.com/NYULibraries/library.nyu.edu-style_guide/blob/gh-pages/index.html)

## Add guides:
* `Create new file` with a `.markdown` extension and write in a combination of HTML and Markdown.
* The page will automatically be added to the front-page list of guides.

## Frontmatter
```yml
---
title: Typography

# guide: 'preview' and 'code example' sections automatically generated
# article: raw content
layout: article # (default: guide)

# Include a code example of the page's content at the bottom of the page
# Must be manually changed to `false` on `guide` layouts
code_example: true

# Appear in sidebar
links:
  links_title: More information (default: Quick Links)
  GitHub: https://github.com/NYULibraries/library.nyu.edu
  Siteleaf Admin: http://manage.siteleaf.com
  # etc.
```

## Content

You can write in Markdown:
```markdown
# Using colors correctly
These are the rules you should follow:
```

Or in HTML:
```HTML
<h1>Using colors correctly</h1>
<p>These are the rules you should follow...</p>
```

Or mix-and-match!
```markdown
# Using colors correctly
<p>These are the rules you should follow...</p>
```

You can even add your own prettified code snippets:
<pre lang="no-highlight"><code>```html
&lt;p&gt;Demonstrate HTML like this&lt;/p&gt;
```

```markdown
# Or some markdown!
```
</code></pre>
