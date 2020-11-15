---
layout: pattern
title: Modal
---

<h1>Modal</h1>


<div class="components-preview">

<dialog open class="modal modal--data-list dropshadow--dark">
  <ul class="data-list">
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
  <ul class="data-list">
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

<dialog open class="modal modal--dialog dropshadow--dark">
  <h4 class="h4">Unsaved changes</h4>

  <p class="body-4 meta-text modal__text">
    Are you sure you want to proceed? You haven’t saved your annotations yet.
  </p>

  <ul class="button-list modal__option-list">
    <li class="button-list__item">
      <button type="button" class="link link--large">Cancel</button>
    </li>
    <li class="button-list__item">
      <button type="button" class="button button--primary">Continue</button>
    </li>
  </ul>
</dialog>

<div></div>

<div></div>

<div></div>

</div>

<div class="components-code" markdown="1">

```html
<dialog open class="modal modal--dialog dropshadow--dark">
  <h4 class="h4">Unsaved changes</h4>

  <p class="body-4 meta-text modal__text">
    Are you sure you want to proceed? You<br />haven’t saved your annotations yet.
  </p>

  <ul class="button-list modal__option-list">
    <li class="button-list__item">
      <button type="button" class="link link--large">Cancel</button>
    </li>
    <li class="button-list__item">
      <button type="button" class="button button--primary">Continue</button>
    </li>
  </ul>
</dialog>
```

</div>

