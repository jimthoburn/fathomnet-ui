---
layout: pattern
title: Chip
---

<h1>Tabs</h1>

<div class="components-preview">

<button type="button" class="chip">
  Chip
  <svg class="icon" aria-label="Delete"><use xlink:href="#icon-close"></use></svg>
</button>

</div>

<div class="components-code" markdown="1">

```html
<button type="button" class="chip">
  Chip
  <svg class="icon" aria-label="Delete"><use xlink:href="#icon-close"></use></svg>
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
            <input type="text" class="search-box__field text-field" placeholder="Animal, mineral, substrate, etc" />
          </label>
          <button type="button" class="chip">
            Chip
            <svg class="icon" aria-label="Delete"><use xlink:href="#icon-close"></use></svg>
          </button>
        </div>
      </li>
      <li class="search-box__item">
        <label class="search-box__label">
          <span class="search-box__label-text">Where</span>
          <input type="text" class="search-box__field text-field" placeholder="Longitude & latitude, basin, etc" />
        </label>
      </li>
      <li class="search-box__item">
        <label class="search-box__label">
          <span class="search-box__label-text">Concept tree</span>
          <select><option>All</option><option>Coming soon…</option></select>
        </label>
      </li>
    </ul>
    <p class="search-box__submit">
      <button type="submit" class="button search-box__button">
        <svg aria-label="Search" class="icon icon--large" width="24" height="24">
          <use xlink:href="#icon-search"></use>
        </svg>
      </button>
    </p>
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
          <input type="text" class="search-box__field text-field" placeholder="Animal, mineral, substrate, etc" />
        </label>
        <button type="button" class="chip">
          Chip
          <svg class="icon" aria-label="Delete"><use xlink:href="#icon-close"></use></svg>
        </button>
      </div>
    </li>
    …
  </ul>
  …
</form>
```

</div>

