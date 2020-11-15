---
layout: pattern
title: Search Box
---

<h1>Search Box</h1>

<div class="components-preview">
  <form class="search-box">
    <ul class="search-box__list">
      <li class="search-box__item">
        <label class="search-box__label">
          <span class="search-box__label-text">What</span>
          <input type="text" class="search-box__field text-field" placeholder="Animal, mineral, substrate, etc" />
        </label>
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
      <label class="search-box__label">
        <span class="search-box__label-text">What</span>
        <input type="text" class="search-box__field text-field" placeholder="Animal, mineral, substrate, etc" />
      </label>
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
```

</div>





<div class="components-preview">
  <header class="header standard-layout__header">
    <div class="header__title-group">
      <h2 class="logotype">
        <a href="/prototype/">FathomNet</a>
      </h2>
      <h1 class="body-2">Explore</h1>
    </div>

    <div class="header__search-box">
      <form class="search-box">
        <ul class="search-box__list">
          <li class="search-box__item">
            <label class="search-box__label">
              <span class="search-box__label-text">What</span>
              <input type="text" class="search-box__field text-field" placeholder="Animal, mineral, substrate, etc" />
            </label>
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

    <ul class="nav">
      <li>
        <a
          href="/sign-in/"
          class="nav__link"
          >
          Sign in
        </a>
      </li>
    </ul>

  </header>
</div>

<div class="components-code" markdown="1">

```html
<header class="header standard-layout__header">
  <div class="header__title-group">
    <h2 class="logotype">
      <a href="/prototype/">FathomNet</a>
    </h2>
    <h1 class="body-2">Explore</h1>
  </div>

  <div class="header__search-box">
    <form class="search-box">
      …
    </form>
  </div>

  <ul class="nav">
    <li>
      <a
        href="/sign-in/"
        class="nav__link"
        >
        Sign in
      </a>
    </li>
  </ul>

</header>
```

</div>

