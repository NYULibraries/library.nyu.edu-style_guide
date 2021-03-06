---
breadcrumbs: true
title: Item Lists
published: true
layout: article
---
<h2 class="heading--block">Link lists</h2>

<ul class="list">
  <li class="menu__li">
    <a href="http://example.org" class="menu__link">Link list item</a>
  </li>
  <li class="menu__li">
    <a href="http://example.org" class="menu__link">Link list item</a>
  </li>
  <li class="menu__li">
    <a href="http://example.org" class="menu__link">Link list item</a>
  </li>
</ul>

```html
<ul class="list">
  <li class="menu__li">
    <a href="http://example.org" class="menu__link">Link list item</a>
  </li>
  <li class="menu__li">
    <a href="http://example.org" class="menu__link">Link list item</a>
  </li>
  <li class="menu__li">
    <a href="http://example.org" class="menu__link">Link list item</a>
  </li>
</ul>
```


<h2 class="heading--block">Item with thumbnail</h2>

<div class="item item--with-thumb">
  <a href="http://example.org">
    <span class="item__image" style="background-image: url('https://placeimg.com/100/100/arch')">Item title</span>
  </a>

  <h1 class="item__title">
    <a href="http://example.org">Item title</a>
  </h1>

  <p>Address, subtitle, or job title</p>

  <p class="item__meta">
    <a href="http://example.org" class="ss-clock meta">Linked meta</a>
    <span class="ss-phone meta">Text meta</span>
  </p>
</div>

```html
<div class="item item--with-thumb">
  <a href="http://example.org">
    <span class="item__image" style="background-image: url('https://placeimg.com/100/100/arch')">Item title</span>
  </a>

  <h1 class="item__title">
    <a href="http://example.org">Item title</a>
  </h1>

  <p>Address, subtitle, or job title</p>

  <p class="item__meta">
    <a href="http://example.org" class="ss-clock meta">Linked meta</a>
    <span class="ss-phone meta">Text meta</span>
  </p>
</div>
```

<div class="flex-blocks">
  <h2 class="heading--block">Item with image</h2>
  <article class="item item--with-image block">
    <a href="http://example.org">
      <span class="item__image" style="background-image: url('https://placeimg.com/400/400/arch')">Item title</span>
    </a>

    <h1 class="item__title">
      <a href="http://example.org">Item title</a>
    </h1>

    <p class="item__meta">
      <a href="http://example.org" class="ss-location meta">Linked meta</a>
    </p>
  </article>
  <article class="item item--with-image block">
    <a href="http://example.org">
      <span class="item__image" style="background-image: url('https://placeimg.com/400/400/arch')">Item title</span>
    </a>

    <h1 class="item__title">
      <a href="http://example.org">Item title</a>
    </h1>

    <p class="item__meta">
      Additional text
    </p>
  </article>
</div>

```html
<div class="flex-blocks">
  <h2 class="heading--block">Item with image</h2>
  <article class="item item--with-image block">
    <a href="http://example.org">
      <span class="item__image" style="background-image: url('https://placeimg.com/400/400/arch')">Item title</span>
    </a>

    <h1 class="item__title">
      <a href="http://example.org">Item title</a>
    </h1>

    <p class="item__meta">
      <a href="http://example.org" class="ss-location meta">Linked meta</a>
    </p>
  </article>

  <article class="item item--with-image block">
    <a href="http://example.org">
      <span class="item__image" style="background-image: url('https://placeimg.com/400/400/arch')">Item title</span>
    </a>

    <h1 class="item__title">
      <a href="http://example.org">Item title</a>
    </h1>

    <p class="item__meta">
      Additional text
    </p>
  </article>
</div>
```
