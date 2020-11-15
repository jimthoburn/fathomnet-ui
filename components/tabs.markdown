---
layout: pattern
title: Tabs
---

<h1>Tabs</h1>


<!--
@TODO: Consider using role="tablist"
https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles/Tab_Role
-->



<div class="components-preview">

<nav
  class="tabs"
  >
  <ul class="tabs__list">
    <li class="tabs__item">
      <a href="" class="tabs__button">
        Day
      </a>
    </li>
    <li class="tabs__item">
      <a href="" class="tabs__button">
        Month
      </a>
    </li>
    <li class="tabs__item">
      <a href="" class="tabs__button">
        Year
      </a>
    </li>
  </ul>
</nav>

</div>

<div class="components-code" markdown="1">

```html
<nav
  class="tabs"
  >
  <ul>
    <li class="tabs__item">
      <a href="" class="tabs__button">
        Day
      </a>
    </li>
    <li class="tabs__item">
      <a href="" class="tabs__button">
        Month
      </a>
    </li>
    <li class="tabs__item">
      <a href="" class="tabs__button">
        Year
      </a>
    </li>
  </ul>
</nav>
```

</div>



<div class="components-preview">

<nav
  class="tabs"
  >
  <ul class="tabs__list">
    <li class="tabs__item">
      <a href="" class="tabs__button">
        Day
      </a>
    </li>
    <li class="tabs__item">
      <a href="" class="tabs__button tabs__button--active">
        Month
      </a>
    </li>
    <li class="tabs__item">
      <a href="" class="tabs__button">
        Year
      </a>
    </li>
  </ul>
</nav>

</div>

<div class="components-code" markdown="1">

```html
<nav
  class="tabs"
  >
  <ul>
    <li class="tabs__item">
      <a href="" class="tabs__button">
        Day
      </a>
    </li>
    <li class="tabs__item">
      <a href="" class="tabs__button tabs__button--active">
        Month
      </a>
    </li>
    <li class="tabs__item">
      <a href="" class="tabs__button">
        Year
      </a>
    </li>
  </ul>
</nav>
```

</div>



<div class="components-preview">

<nav
  class="tabs"
  >
  <ul class="tabs__list">
    <li class="tabs__item">
      <a href="" class="tabs__button tabs__button--active">
        Day
      </a>
    </li>
    <li class="tabs__item">
      <a href="" class="tabs__button">
        Month
      </a>
    </li>
    <li class="tabs__item">
      <a href="" class="tabs__button">
        Year
      </a>
    </li>
  </ul>
</nav>

</div>

<div class="components-code" markdown="1">

```html
<nav
  class="tabs"
  >
  <ul>
    <li class="tabs__item">
      <a href="" class="tabs__button tabs__button--active">
        Day
      </a>
    </li>
    <li class="tabs__item">
      <a href="" class="tabs__button">
        Month
      </a>
    </li>
    <li class="tabs__item">
      <a href="" class="tabs__button">
        Year
      </a>
    </li>
  </ul>
</nav>
```

</div>





<div class="components-preview">

<nav
  class="explore-tabs"
  >
  <ul class="explore-tabs__list">
    <li class="explore-tabs__item">
      <a href="" class="explore-tabs__button">
        <svg class="icon explore-tabs__icon" aria-label="Map"><use xlink:href="#icon-map"></use></svg>
      </a>
    </li>
    <li class="explore-tabs__item">
      <a href="" class="explore-tabs__button explore-tabs__button--active">
        <svg class="icon explore-tabs__icon" aria-label="Tree"><use xlink:href="#icon-label-tree"></use></svg>
      </a>
    </li>
  </ul>
</nav>

</div>

<div class="components-code" markdown="1">

```html
<nav
  class="explore-tabs"
  >
  <ul class="explore-tabs__list">
    <li class="explore-tabs__item">
      <a href="" class="explore-tabs__button">
        <svg class="icon explore-tabs__icon" aria-label="Map"><use xlink:href="#icon-map"></use></svg>
      </a>
    </li>
    <li class="explore-tabs__item">
      <a href="" class="explore-tabs__button explore-tabs__button--active">
        <svg class="icon explore-tabs__icon" aria-label="Tree"><use xlink:href="#icon-label-tree"></use></svg>
      </a>
    </li>
  </ul>
</nav>
```

</div>




<div class="components-preview">

<nav
  class="explore-tabs explore-tabs--vertical"
  >
  <ul class="explore-tabs__list">
    <li class="explore-tabs__item">
      <a href="" class="explore-tabs__button">
        <svg class="icon explore-tabs__icon" aria-label="Zoom in"><use xlink:href="#icon-plus"></use></svg>
      </a>
    </li>
    <li class="explore-tabs__item">
      <a href="" class="explore-tabs__button">
        <svg class="icon explore-tabs__icon" aria-label="Zoom out"><use xlink:href="#icon-minus"></use></svg>
      </a>
    </li>
  </ul>
</nav>

</div>

<div class="components-code" markdown="1">

```html
<nav
  class="explore-tabs explore-tabs--vertical"
  >
  <ul class="explore-tabs__list">
    <li class="explore-tabs__item">
      <a href="" class="explore-tabs__button">
        <svg class="icon explore-tabs__icon" aria-label="Zoom in"><use xlink:href="#icon-plus"></use></svg>
      </a>
    </li>
    <li class="explore-tabs__item">
      <a href="" class="explore-tabs__button">
        <svg class="icon explore-tabs__icon" aria-label="Zoom out"><use xlink:href="#icon-minus"></use></svg>
      </a>
    </li>
  </ul>
</nav>
```

</div>

