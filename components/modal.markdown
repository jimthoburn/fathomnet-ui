---
layout: pattern
title: Modal
---

<h1>Modal</h1>


<div class="components-preview">

<dialog open class="modal modal--data-list dropshadow--dark">
  <ul class="data-list modal__data-list">
    {% for index in (1..20) %}
    <li class="data-list__item">
      <button type="button" class="data-list__button">
        Ampeliscidae
      </button>
    </li>
    <li class="data-list__item">
      <button type="button" class="data-list__button">
        Ampharetidae
      </button>
    </li>
    <li class="data-list__item">
      <button type="button" class="data-list__button">
        Amphascandria
      </button>
    </li>
    <li class="data-list__item">
      <button type="button" class="data-list__button">
        Ampheraster
      </button>
    </li>
    {% endfor %}
  </ul>
</dialog>

<div></div>

<div></div>

</div>

<div class="components-code" markdown="1">

```html
<dialog open class="modal modal--data-list dropshadow--dark">
  <ul class="data-list modal__data-list">
    <li class="data-list__item">
      <button type="button" class="data-list__button">
        Ampeliscidae
      </button>
    </li>
    <li class="data-list__item">
      <button type="button" class="data-list__button">
        Ampharetidae
      </button>
    </li>
    <li class="data-list__item">
      <button type="button" class="data-list__button">
        Amphascandria
      </button>
    </li>
    <li class="data-list__item">
      <button type="button" class="data-list__button">
        Ampheraster
      </button>
    </li>
  </ul>
</dialog>
```

</div>


<div class="components-preview">

<dialog open class="modal modal--data-list dropshadow--dark">
  <!-- <label class="field field--has-placeholder field--has-icon">
    <span class="field__label">Search</span>
    <input
      type="text"
      value=""
      placeholder="Search…"
      class="field__input"
      />
    <svg class="icon field__icon"><use xlink:href="#icon-search"></use></svg>
  </label> -->
  <ul class="data-list modal__data-list">
    <li class="data-list__item">
      <label class="data-list__field">
        <input type="checkbox" class="data-list__field-checkbox" />
        Expert
      </label>
    </li>
    <li class="data-list__item">
      <label class="data-list__field">
        <input type="checkbox" class="data-list__field-checkbox" />
        Intermediate
      </label>
    </li>
    <li class="data-list__item">
      <label class="data-list__field">
        <input type="checkbox" class="data-list__field-checkbox" />
        Novice
      </label>
    </li>
  </ul>
  <ul class="button-list modal__mini-option-list">
    <li class="button-list__item modal__mini-option-list-item">
      <button type="button" class="link link--medium link--primary">Clear</button>
    </li>
    <li class="button-list__item modal__mini-option-list-item">
      <button type="button" class="button button--medium button--primary">Save</button>
    </li>
  </ul>
</dialog>

<div></div>

<div></div>

</div>

<div class="components-code" markdown="1">

```html
<dialog open class="modal modal--data-list dropshadow--dark">
  <ul class="data-list modal__data-list">
    <li class="data-list__item">
      <label class="data-list__field">
        <input type="checkbox" class="data-list__field-checkbox" />
        Expert
      </label>
    </li>
    <li class="data-list__item">
      <label class="data-list__field">
        <input type="checkbox" class="data-list__field-checkbox" />
        Intermediate
      </label>
    </li>
    <li class="data-list__item">
      <label class="data-list__field">
        <input type="checkbox" class="data-list__field-checkbox" />
        Novice
      </label>
    </li>
  </ul>
  <ul class="button-list modal__mini-option-list">
    <li class="button-list__item modal__mini-option-list-item">
      <button type="button" class="link link--medium link--primary">Clear</button>
    </li>
    <li class="button-list__item modal__mini-option-list-item">
      <button type="button" class="button button--medium button--primary">Save</button>
    </li>
  </ul>
</dialog>
```

</div>



<div class="components-preview">

<dialog open class="modal modal--data-list dropshadow--dark">
  <label class="field field--has-placeholder field--has-icon modal__field">
    <span class="field__label">Search</span>
    <input
      type="search"
      value=""
      placeholder="Search…"
      class="field__input"
      />
    <svg class="icon field__icon"><use xlink:href="#icon-search"></use></svg>
  </label>
  <ul class="data-list modal__data-list">
    {% for index in (1..20) %}
    <li class="data-list__item">
      <label class="data-list__field">
        <input type="checkbox" class="data-list__field-checkbox" />
        Contributor name
      </label>
    </li>
    {% endfor %}
  </ul>
  <ul class="button-list modal__mini-option-list">
    <li class="button-list__item modal__mini-option-list-item">
      <button type="button" class="link link--medium link--primary">Clear</button>
    </li>
    <li class="button-list__item modal__mini-option-list-item">
      <button type="button" class="button button--medium button--primary">Save</button>
    </li>
  </ul>
</dialog>

<div></div>

<div></div>

<div></div>

<div></div>

<div></div>

</div>

<div class="components-code" markdown="1">

```html
<dialog open class="modal modal--data-list dropshadow--dark">
  <label class="field field--has-placeholder field--has-icon modal__field">
    <span class="field__label">Search</span>
    <input
      type="search"
      value=""
      placeholder="Search…"
      class="field__input"
      />
    <svg class="icon field__icon"><use xlink:href="#icon-search"></use></svg>
  </label>
  <ul class="data-list modal__data-list">
    <li class="data-list__item">
      <label class="data-list__field">
        <input type="checkbox" class="data-list__field-checkbox" />
        Contributor name
      </label>
    </li>
    <li class="data-list__item">…</li>
    <li class="data-list__item">…</li>
    <li class="data-list__item">…</li>
    …
  </ul>
  <ul class="button-list modal__mini-option-list">
    <li class="button-list__item modal__mini-option-list-item">
      <button type="button" class="link link--medium link--primary">Clear</button>
    </li>
    <li class="button-list__item modal__mini-option-list-item">
      <button type="button" class="button button--medium button--primary">Save</button>
    </li>
  </ul>
</dialog>
```

</div>



<div class="components-preview">

<dialog open class="modal modal--dialog dropshadow--dark" style="position: absolute; top: unset; transform: unset;">
  <h4 class="h4">Unsaved changes</h4>

  <p class="body-4 text-meta modal__text">
    Are you sure you want to proceed? You haven’t saved your annotations yet.
  </p>

  <ul class="button-list modal__option-list">
    <li class="button-list__item modal__option-list-item">
      <button type="button" class="link link--primary modal__option-link">Cancel</button>
    </li>
    <li class="button-list__item modal__option-list-item">
      <button type="button" class="button button--primary">Continue</button>
    </li>
  </ul>
</dialog>

<div></div>

<div></div>

<div></div>

<div></div>

<div></div>

</div>

<div class="components-code" markdown="1">

```html
<dialog open class="modal modal--dialog dropshadow--dark">
  <h4 class="h4">Unsaved changes</h4>

  <p class="body-4 text-meta modal__text">
    Are you sure you want to proceed? You<br />haven’t saved your annotations yet.
  </p>

  <ul class="button-list modal__option-list">
    <li class="button-list__item">
      <button type="button" class="link link--primary modal__option-link">Cancel</button>
    </li>
    <li class="button-list__item">
      <button type="button" class="button button--primary">Continue</button>
    </li>
  </ul>
</dialog>
```

</div>

