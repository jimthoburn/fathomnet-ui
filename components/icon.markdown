---
layout: default
---

<h1>Icon</h1>

<div class="components-preview">

  <svg aria-label="Add" class="icon">
    <title>Plus</title>
    <use xlink:href="#icon-plus"></use>
  </svg>

</div>

<div class="components-code" markdown="1">

```html
<svg aria-label="Add" class="icon">
  <use xlink:href="#icon-plus"></use>
</svg>
```

You can use an `aria-label` attribute on an `<svg />` element for the same purpose that you might use an `alt` attribute for an `<img />` element.

</div>

<div class="components-preview">

  <a href="/">
    <svg class="icon">
      <use xlink:href="#icon-plus"></use>
    </svg>
    Add
  </a>

</div>

<div class="components-code" markdown="1">

```html
<a href="/">
  <svg class="icon">
    <use xlink:href="#icon-plus"></use>
  </svg>
  Add
</a>
```

It’s okay to leave out the `aria-label` attribute if there’s already some text nearby that gives context.

</div>

