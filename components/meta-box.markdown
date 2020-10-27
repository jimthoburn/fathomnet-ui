---
layout: pattern
title: Meta box
---

<style>
.meta-box {
  min-width: 25em;
}
</style>

<h1>Meta box</h1>



<div class="components-preview">

<details class="meta-box">
  <summary class="meta-box__summary">
    <h2 class="meta-box__heading">Concepts <em class="text-meta">8</em></h2>
    <svg class="icon icon--large meta-box__close-icon" width="24" height="24">
      <use xlink:href="#icon-minus"></use>
    </svg>
    <svg class="icon icon--large meta-box__open-icon" width="24" height="24">
      <use xlink:href="#icon-plus"></use>
    </svg>
  </summary>
  <ul class="meta-box__list">
    {% for index in (1..8) %}
    <li class="meta-box__list-item">
      <a href="/" class="link-hit-area">
        <strong class="body-1 link-hit-area__active-indicator">Amphiprion ocellaris</strong>
        <br />
        <span class="text-meta label-1">Verified by Sabrina Coombes on 10/06/20</span>
      </a>
    </li>
    {% endfor %}
  </ul>
</details>

</div>

<div class="components-code" markdown="1">

```html
<details class="meta-box"></details>
```

</div>



<div class="components-preview">

<details class="meta-box" open>
  <summary class="meta-box__summary">
    <h2 class="meta-box__heading">Concepts <em class="text-meta">8</em></h2>
    <svg class="icon icon--large meta-box__close-icon" width="24" height="24">
      <use xlink:href="#icon-minus"></use>
    </svg>
    <svg class="icon icon--large meta-box__open-icon" width="24" height="24">
      <use xlink:href="#icon-plus"></use>
    </svg>
  </summary>
  <ul class="meta-box__list">
    {% for index in (1..8) %}
    <li class="meta-box__list-item">
      <a href="/" class="link-hit-area">
        <strong class="body-1 link-hit-area__active-indicator">Amphiprion ocellaris</strong>
        <br />
        <span class="text-meta label-1">Verified by Sabrina Coombes on 10/06/20</span>
      </a>
    </li>
    {% endfor %}
  </ul>
</details>

</div>

<div class="components-code" markdown="1">

```html
<details class="meta-box" open></details>
```

</div>



<div class="components-preview">

<details class="meta-box">
  <summary class="meta-box__summary">
    <h2 class="meta-box__heading">Title <em class="text-meta">Number</em></h2>
    <svg class="icon icon--large meta-box__close-icon" width="24" height="24">
      <use xlink:href="#icon-minus"></use>
    </svg>
    <svg class="icon icon--large meta-box__open-icon" width="24" height="24">
      <use xlink:href="#icon-plus"></use>
    </svg>
  </summary>
  <ul class="meta-box__list">
    {% for index in (1..8) %}
    <li class="meta-box__list-item">
      <a href="/" class="link-hit-area">
        <strong class="body-1 link-hit-area__active-indicator">Amphiprion ocellaris</strong>
        <br />
        <span class="text-meta label-1">Verified by Sabrina Coombes on 10/06/20</span>
      </a>
    </li>
    {% endfor %}
  </ul>
</details>

</div>

<div class="components-code" markdown="1">

```html
<summary class="meta-box__summary">
  <h2 class="meta-box__heading">Title <em class="text-meta">Number</em></h2>
  <svg class="icon icon--large meta-box__close-icon" width="24" height="24">
    <use xlink:href="#icon-minus"></use>
  </svg>
  <svg class="icon icon--large meta-box__open-icon" width="24" height="24">
    <use xlink:href="#icon-plus"></use>
  </svg>
</summary>
```

</div>




<div class="components-preview">

<details open class="meta-box">
  <summary class="meta-box__summary">
    <h2 class="meta-box__heading">Collections <em class="text-meta">16</em></h2>
    <svg class="icon icon--large meta-box__close-icon" width="24" height="24">
      <use xlink:href="#icon-minus"></use>
    </svg>
    <svg class="icon icon--large meta-box__open-icon" width="24" height="24">
      <use xlink:href="#icon-plus"></use>
    </svg>
  </summary>
  <ul class="meta-box__list">
    {% for index in (1..8) %}
    <li class="meta-box__list-item">
      <a href="/">amei_i110703_b2</a> from <a href="/">Letitia Stewart</a>
    </li>
    <li class="meta-box__list-item">
      <a href="/">dkla_j34091_a8</a> from <a href="/">Courtenay Bruce</a>
    </li>
    {% endfor %}
  </ul>
</details>

</div>

<div class="components-code" markdown="1">

```html
<details open class="meta-box">
  <summary class="meta-box__summary">…</summary>

  <ul class="meta-box__list">
    <li class="meta-box__list-item">
      <a href="/">amei_i110703_b2</a> from <a href="/">Letitia Stewart</a>
    </li>

    <li class="meta-box__list-item">…</li>
    <li class="meta-box__list-item">…</li>
    <li class="meta-box__list-item">…</li>
    …
  </ul>
</details>
```

</div>



<div class="components-preview">

<details open class="meta-box">
  <summary class="meta-box__summary">
    <h2 class="meta-box__heading">Concepts <em class="text-meta">8</em></h2>
    <svg class="icon icon--large meta-box__close-icon" width="24" height="24">
      <use xlink:href="#icon-minus"></use>
    </svg>
    <svg class="icon icon--large meta-box__open-icon" width="24" height="24">
      <use xlink:href="#icon-plus"></use>
    </svg>
  </summary>
  <ul class="meta-box__list">
    {% for index in (1..8) %}
    <li class="meta-box__list-item">
      <a href="/" class="link-hit-area">
        <strong class="body-1 link-hit-area__active-indicator">Amphiprion ocellaris</strong>
        <br />
        <span class="text-meta label-1">Verified by Sabrina Coombes on 10/06/20</span>
      </a>
    </li>
    {% endfor %}
  </ul>
</details>

</div>

<div class="components-code" markdown="1">

```html
<details open class="meta-box">
  <summary class="meta-box__summary">…</summary>

  <ul class="meta-box__list">
    <li class="meta-box__list-item">
      <a href="/" class="link-hit-area">
        <strong class="body-1 link-hit-area__active-indicator">Amphiprion ocellaris</strong>
        <br />
        <span class="text-meta label-1">Verified by Sabrina Coombes on 10/06/20</span>
      </a>
    </li>

    <li class="meta-box__list-item">…</li>
    <li class="meta-box__list-item">…</li>
    <li class="meta-box__list-item">…</li>
    …
  </ul>
</details>
```

</div>



<div class="components-preview">

<details open class="meta-box">
  <summary class="meta-box__summary">
    <h2 class="meta-box__heading">Details</h2>
    <svg class="icon icon--large meta-box__close-icon" width="24" height="24">
      <use xlink:href="#icon-minus"></use>
    </svg>
    <svg class="icon icon--large meta-box__open-icon" width="24" height="24">
      <use xlink:href="#icon-plus"></use>
    </svg>
  </summary>
  <dl class="meta-box__description-list">
    <dt class="meta-box__description-title">Location</dt>
    <dd class="meta-box__description-data">East Indian Ocean</dd>
    <dd class="meta-box__description-data">-20° 00' 0.00" S, 80° 00' 0.00" E</dd>

    <dt class="meta-box__description-title">Depth</dt>
    <dd class="meta-box__description-data">-823 m</dd>

    <dt class="meta-box__description-title">Date</dt>
    <dd class="meta-box__description-data">09/30/20</dd>

    <dt class="meta-box__description-title">Title</dt>
    <dd class="meta-box__description-data">Data</dd>

    <dt class="meta-box__description-title">Title</dt>
    <dd class="meta-box__description-data">Data</dd>

    <dt class="meta-box__description-title">Title</dt>
    <dd class="meta-box__description-data">Data</dd>
  </dl>
</details>

</div>

<div class="components-code" markdown="1">

```html
<details open class="meta-box">
  <summary class="meta-box__summary">…</summary>

  <dl class="meta-box__description-list">
    <dt class="meta-box__description-title">Location</dt>
    <dd class="meta-box__description-data">East Indian Ocean</dd>
    <dd class="meta-box__description-data">-20° 00' 0.00" S, 80° 00' 0.00" E</dd>

    <dt class="meta-box__description-title">…</dt>
    <dd class="meta-box__description-data">…</dd>

    <dt class="meta-box__description-title">…</dt>
    <dd class="meta-box__description-data">…</dd>

    …
  </dl>
</details>
```

</div>

