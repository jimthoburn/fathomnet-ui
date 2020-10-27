---
layout: pattern
title: Card
---

<h1>Card</h1>

<div class="components-preview">

<ul class="card-list" style="justify-self: stretch;">

{% for index in (1..6) %}

<li class="card-list__item">

  <a href="/" class="card">

    <span class="card__image">
      <img src="/images/mbari/827b8c03a21bebd5ac8cef5ad169ebfab9aafbc9.png" alt="Amphiprion ocellaris" />
    </span>

    <span class="card__text">
      <span class="card__name">
        <strong class="text-single-line">
          Amphiprion ocellaris, also known as the false percula clownfish
          or common clownfish, is a marine fish belonging to the family Pomacentridae
        </strong>
        <small>(+4 more)</small>
      </span>
      <br />
      <span class="card__meta text-single-line">
        Contributor name, collection name, other meta data about this item
      </span>
    </span>

  </a>

</li>

<li class="card-list__item">

  <a href="/" class="card">

    <span class="card__image">
      <img src="/images/mbari/ee2ec6e6c08e195cde7f8542286da55ab1648249.png" alt="Amphiprion ocellaris" />
    </span>

    <span class="card__text">
      <span class="card__name">
        <strong class="text-single-line">
          Amphiprion ocellaris, also known as the false percula clownfish
          or common clownfish, is a marine fish belonging to the family Pomacentridae
        </strong>
        <small>(+4 more)</small>
      </span>
      <br />
      <span class="card__meta text-single-line">
        Contributor name, collection name, other meta data about this item
      </span>
    </span>

  </a>

</li>

{% endfor %}

</ul>

</div>

<div class="components-code" markdown="1">

```html
<ul class="card-list">

  <li class="card-list__item">

    <a href="/" class="card">

      <span class="card__image">
        <img src="…" alt="Amphiprion ocellaris" />
      </span>

      <span class="card__text">
        <span class="card__name">
          <strong class="text-single-line">
            Amphiprion ocellaris, also known as the false percula clownfish
            or common clownfish, is a marine fish belonging to the family Pomacentridae
          </strong>
          <small>(+4 more)</small>
        </span>
        <br />
        <span class="card__meta text-single-line">
          Contributor name, collection name, other meta data about this item
        </span>
      </span>

    </a>

  </li>
  <li class="card-list__item card">…</li>
  <li class="card-list__item card">…</li>

</ul>
```

</div>
