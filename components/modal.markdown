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
  <form>
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
        <button type="submit" class="button button--medium button--primary">Save</button>
      </li>
      <li class="button-list__item modal__mini-option-list-item">
        <button type="reset" class="link link--medium link--primary">Clear</button>
      </li>
    </ul>
  </form>
</dialog>

<div></div>

<div></div>

</div>

<div class="components-code" markdown="1">

```html
<dialog open class="modal modal--data-list dropshadow--dark">
  <form>
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
        <button type="submit" class="button button--medium button--primary">Save</button>
      </li>
      <li class="button-list__item modal__mini-option-list-item">
        <button type="reset" class="link link--medium link--primary">Clear</button>
      </li>
    </ul>
  </form>
</dialog>
```

</div>



<div class="components-preview">

<dialog open class="modal modal--data-list dropshadow--dark">
  <form>
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
        <button type="submit" class="button button--medium button--primary">Save</button>
      </li>
      <li class="button-list__item modal__mini-option-list-item">
        <button type="reset" class="link link--medium link--primary">Clear</button>
      </li>
    </ul>
  </form>
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
  <form>
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
        <button type="submit" class="button button--medium button--primary">Save</button>
      </li>
      <li class="button-list__item modal__mini-option-list-item">
        <button type="reset" class="link link--medium link--primary">Clear</button>
      </li>
    </ul>
  </form>
</dialog>
```

</div>





<div class="components-preview">

<dialog open class="modal modal--data-list dropshadow--dark">
  <form>
    <ol class="field-list">
      <li class="field-list__item">
        <label class="field field--has-container modal__field">
          <span class="field__label">Start</span>
          <span class="field__container">
            <input
              type="time"
              class="field__input"
              />
          </span>
        </label>
      </li>
      <li>
        <label class="field field--has-container modal__field">
          <span class="field__label">End</span>
          <span class="field__container">
            <input
              type="time"
              class="field__input"
              />
          </span>
        </label>
      </li>
    </ol>
    <ul class="button-list modal__mini-option-list">
      <li class="button-list__item modal__mini-option-list-item">
        <button type="submit" class="button button--medium button--primary">Save</button>
      </li>
      <li class="button-list__item modal__mini-option-list-item">
        <button type="reset" class="link link--medium link--primary">Clear</button>
      </li>
    </ul>
  </form>
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
  <form>
    <ol class="field-list">
      <li class="field-list__item">
        <label class="field field--has-container modal__field">
          <span class="field__label">Start</span>
          <span class="field__container">
            <input
              type="time"
              class="field__input"
              />
          </span>
        </label>
      </li>
      <li>
        <label class="field field--has-container modal__field">
          <span class="field__label">End</span>
          <span class="field__container">
            <input
              type="time"
              class="field__input"
              />
          </span>
        </label>
      </li>
    </ol>
    <ul class="button-list modal__mini-option-list">
      <li class="button-list__item modal__mini-option-list-item">
        <button type="submit" class="button button--medium button--primary">Save</button>
      </li>
      <li class="button-list__item modal__mini-option-list-item">
        <button type="reset" class="link link--medium link--primary">Clear</button>
      </li>
    </ul>
  </form>
</dialog>
```

</div>







<div class="components-preview">

<dialog open class="modal modal--data-list dropshadow--dark">
  <form>
    <fieldset class="tabs modal__field">
      <legend class="field__label">Timeframe</legend>
      <ol class="tabs__list">
        <li class="tabs__item">
          <label>
            <input type="radio" name="timeframe" value="day" class="tabs__radio" checked />
            <span class="tabs__button">
              Day
            </span>
          </label>
        </li>
        <li class="tabs__item">
          <label>
            <input type="radio" name="timeframe" value="month" class="tabs__radio" />
            <span class="tabs__button">
              Month
            </span>
          </label>
        </li>
        <li class="tabs__item">
          <label>
            <input type="radio" name="timeframe" value="year" class="tabs__radio" />
            <span class="tabs__button">
              Year
            </span>
          </label>
        </li>
      </ol>
    </fieldset>
    <ol class="field-list">
      <li class="field-list__item">
        <label class="field field--has-container modal__field">
          <span class="field__label">Start</span>
          <span class="field__container">
            <input
              type="date"
              class="field__input"
              />
          </span>
        </label>
      </li>
      <li class="field-list__item">
        <label class="field field--has-container modal__field">
          <span class="field__label">End</span>
          <span class="field__container">
            <input
              type="date"
              class="field__input"
              />
          </span>
        </label>
      </li>
    </ol>
    <ul class="button-list modal__mini-option-list">
      <li class="button-list__item modal__mini-option-list-item">
        <button type="submit" class="button button--medium button--primary">Save</button>
      </li>
      <li class="button-list__item modal__mini-option-list-item">
        <button type="reset" class="link link--medium link--primary">Clear</button>
      </li>
    </ul>
  </form>
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
  <form>
    <fieldset class="tabs modal__field">
      <legend class="field__label">Timeframe</legend>
      <ol class="tabs__list">
        <li class="tabs__item">
          <label>
            <input type="radio" name="timeframe" value="day" class="tabs__radio" checked />
            <span class="tabs__button">
              Day
            </span>
          </label>
        </li>
        <li class="tabs__item">…</li>
        <li class="tabs__item">…</li>
      </ol>
    </fieldset>
    <ol class="field-list">
      <li class="field-list__item">
        <label class="field field--has-container modal__field">
          <span class="field__label">Start</span>
          <span class="field__container">
            <input
              type="date"
              class="field__input"
              />
          </span>
        </label>
      </li>
      <li class="field-list__item">…</li>
    </ol>
    <ul class="button-list modal__mini-option-list">
      <li class="button-list__item modal__mini-option-list-item">
        <button type="submit" class="button button--medium button--primary">Save</button>
      </li>
      <li class="button-list__item modal__mini-option-list-item">
        <button type="reset" class="link link--medium link--primary">Clear</button>
      </li>
    </ul>
  </form>
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
      <button type="button" class="button button--primary">Continue</button>
    </li>
    <li class="button-list__item modal__option-list-item">
      <button type="button" class="link link--primary modal__option-link">Cancel</button>
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
    Are you sure you want to proceed? You haven’t saved your annotations yet.
  </p>

  <ul class="button-list modal__option-list">
    <li class="button-list__item modal__option-list-item">
      <button type="button" class="button button--primary">Continue</button>
    </li>
    <li class="button-list__item modal__option-list-item">
      <button type="button" class="link link--primary modal__option-link">Cancel</button>
    </li>
  </ul>
</dialog>
```

</div>

