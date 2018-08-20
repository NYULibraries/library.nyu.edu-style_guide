---
title: Live Editing
layout: article
links:
  Writing in Markdown: "/library.nyu.edu-style_guide/guides/markdown"
---

<link rel="stylesheet" type="text/css" href="{{ "/assets/wmd/wmd.css" | prepend: site.baseurl }}"/>
<script type="text/javascript" src="{{ "/assets/wmd/wmd.combined.min.js" | prepend: site.baseurl }}"></script>
<h1>Markdown Editor</h1>
<div>
  <div id="button-row" style="display: none;"></div>
  <textarea id="live-markdown" name="copy"
    rows="10"
    placeholder="Enter your Markdown here."></textarea>
  <div id="preview"></div>
</div>

# Shortcut Keys

**(Windows Users: ⌘ → `Ctrl`)**

* bold: ⌘ + b
* italic: ⌘ + i
* link: ⌘ + l
* quote: ⌃ + q
* code: ⌘ + k
* image: ⌘ + g
* ordered list: ⌘ + o
* unordered list: ⌘ + u
* heading: ⌘ + h
* horizontal line: ⌘ + r
* redo: ⌘ + y
* undo: ⌘ + z

### Missing features:
* Link modifiers (e.g. `{: .button}`)

<label for="copy_html">HTML Output</label>
<input type="text" name="copy_html" value="" id="copy_html">

<script type="text/javascript">
  setup_wmd({
    input: "live-markdown",
    preview: "preview",
    output: "copy_html",
    button_bar: "button-row"
  });
</script>
