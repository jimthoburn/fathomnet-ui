---
layout: pattern
title: Icon

icons:
  - label: Alert
    id: alert

  - label: Arrow Left
    id: arrow-left

  - label: Arrow Right
    id: arrow-right

  - label: Check
    id: check

  - label: Chevron Down
    id: chevron-down

  - label: Close
    id: close

  - label: Expand
    id: expand

  - label: Label Tree
    id: label-tree

  - label: Lock
    id: lock

  - label: Map
    id: map

  - label: Menu
    id: menu

  - label: Minimize
    id: minimize

  - label: Minus
    id: minus

  - label: Plus
    id: plus

  - label: Search
    id: search

  - label: Edit
    id: edit

  - label: Image
    id: image

  - label: Download
    id: download

---

<h1>Icon</h1>


<div class="components-preview">

  <svg class="icon icon--large" width="24" height="24">
    <use xlink:href="#icon-map"></use>
  </svg>

</div>

<div class="components-code" markdown="1">

```html
<svg class="icon" width="24" height="24">
  <use xlink:href="#icon-map"></use>
</svg>
```

</div>

<div class="components-preview components-preview--grid">

  {% for icon in page.icons %}
  <div class="components-icon">
    <svg aria-label="{{ icon.label }}" class="icon icon--large" width="24" height="24">
      <use xlink:href="#icon-{{ icon.id }}"></use>
    </svg>
    <br />
    {{ icon.label }}
    <br />
    <code>icon-{{ icon.id }}</code>
  </div>
  {% endfor %}

</div>

<div class="components-code" markdown="1">
</div>


<div class="components-preview">

  <svg
    class="icon icon--large"
    width="24" height="24"
    >
    <use xlink:href="#icon-check"></use>
  </svg>

  <svg
    class="icon icon--small"
    width="24" height="24"
    >
    <use xlink:href="#icon-check"></use>
  </svg>

  <svg
    class="icon icon--extra-small"
    width="24" height="24"
    >
    <use xlink:href="#icon-check"></use>
  </svg>

  <svg class="icon icon--large" width="24" height="24">
    <use xlink:href="#icon-map"></use>
  </svg>

  <svg class="icon icon--small" width="24" height="24">
    <use xlink:href="#icon-map"></use>
  </svg>

  <svg class="icon icon--extra-small" width="24" height="24">
    <use xlink:href="#icon-map"></use>
  </svg>

</div>

<div class="components-code" markdown="1">

```html
<svg
  class="icon icon--large"
  width="24" height="24"
  >
  <use xlink:href="#icon-check"></use>
</svg>

<svg
  class="icon icon--small"
  width="24" height="24"
  >
  <use xlink:href="#icon-check"></use>
</svg>

<svg
  class="icon icon--extra-small"
  width="24" height="24"
  >
  <use xlink:href="#icon-check"></use>
</svg>
```

</div>

<div class="components-preview">

  <a href="/">
    <svg aria-label="Show map" class="icon" width="24" height="24">
      <use xlink:href="#icon-map"></use>
    </svg>
  </a>

</div>

<div class="components-code" markdown="1">

```html
<a href="/">
  <svg aria-label="Show map" class="icon" width="24" height="24">
    <use xlink:href="#icon-map"></use>
  </svg>
</a>
```

If an icon is used in place of text content, you can use an `aria-label` attribute to make the text available for software–such as screen readers and search engines.
<small>(Similar to an `alt` attribute for an `<img />` element)</small>

</div>

<div class="components-preview">

  <p class="loading">
    <span class="loading__dots"></span>
    <span class="loading__text">Loading</span>
  </p>

</div>

<div class="components-code" markdown="1">

```html
<p class="loading">
  <span class="loading__dots"></span>
  <span class="loading__text">Loading</span>
</p>
```

</div>

