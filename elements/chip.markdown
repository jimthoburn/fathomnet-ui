---
layout: pattern
title: Chip
---

<h1>Tabs</h1>

<div class="components-preview">

<button type="button" class="chip">
  Chip
  <svg class="icon icon--extra-small" aria-label="Delete"><use xlink:href="#icon-close"></use></svg>
</button>

</div>

<div class="components-code" markdown="1">

```html
<button type="button" class="chip">
  Chip
  <svg class="icon icon--extra-small" aria-label="Delete"><use xlink:href="#icon-close"></use></svg>
</button>
```

</div>





<div class="components-preview">
  <form class="search-box">
    <ul class="search-box__list">
      <li class="search-box__item">
        <div class="search-box__label">
          <label>
            <span class="search-box__label-text">What</span>
            <!-- <input type="text" class="search-box__field text-field" placeholder="Animal, mineral, substrate, etc" /> -->
          </label>
          <button type="button" class="chip">
            Ampeliscidae
            <svg class="icon icon--extra-small" aria-label="Delete"><use xlink:href="#icon-close"></use></svg>
          </button>
          <button type="button" class="chip">
            Ampharetidae
            <svg class="icon icon--extra-small" aria-label="Delete"><use xlink:href="#icon-close"></use></svg>
          </button>
          <button type="button" class="chip">
            Amphascandria
            <svg class="icon icon--extra-small" aria-label="Delete"><use xlink:href="#icon-close"></use></svg>
          </button>
          <button type="button" class="chip">
            Ampheraster
            <svg class="icon icon--extra-small" aria-label="Delete"><use xlink:href="#icon-close"></use></svg>
          </button>
        </div>
      </li>
    </ul>
  </form>
</div>

<div class="components-code" markdown="1">

```html
<form class="search-box">
  <ul class="search-box__list">
    <li class="search-box__item">
      <div class="search-box__label">
        <label>
          <span class="search-box__label-text">What</span>
          <!--
          @TODO Hidden until “Chip” is pressed?
          <input type="text" class="search-box__field text-field" placeholder="Animal, mineral, substrate, etc" />
          -->
        </label>
        <button type="button" class="chip">
          Ampeliscidae
          <svg class="icon icon--extra-small" aria-label="Delete"><use xlink:href="#icon-close"></use></svg>
        </button>
        <button type="button" class="chip">
          Ampharetidae
          <svg class="icon icon--extra-small" aria-label="Delete"><use xlink:href="#icon-close"></use></svg>
        </button>
        <button type="button" class="chip">
          Amphascandria
          <svg class="icon icon--extra-small" aria-label="Delete"><use xlink:href="#icon-close"></use></svg>
        </button>
        <button type="button" class="chip">
          Ampheraster
          <svg class="icon icon--extra-small" aria-label="Delete"><use xlink:href="#icon-close"></use></svg>
        </button>
      </div>
    </li>
    …
  </ul>
  …
</form>
```

</div>

