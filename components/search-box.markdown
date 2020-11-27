---
layout: pattern
title: Search box
---

<h1>Search box</h1>

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
          <details>
            <summary class="search-box__dropdown-button dropdown-button">
              WoRMS
              <svg class="icon icon--small" width="24" height="24">
                <use xlink:href="#icon-chevron-down"></use>
              </svg>
            </summary>
            <div class="modal modal--data-list dropshadow--dark">
              <ul class="data-list">
                <li class="data-list__item">
                  <button type="button" class="data-list__button">
                    MBARI
                  </button>
                </li>
                <li class="data-list__item">
                  <button type="button" class="data-list__button">
                    WoRMS
                  </button>
                </li>
              </ul>
            </div>
          </details>
        </label>
      </li>
    </ul>
    <p class="search-box__submit">
      <button type="submit" class="button button--tertiary button--round search-box__button">
        <svg aria-label="Search" class="icon icon--small" width="24" height="24">
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
        <details>
          <summary class="search-box__dropdown-button dropdown-button">
            WoRMS
            <svg class="icon icon--small" width="24" height="24">
              <use xlink:href="#icon-chevron-down"></use>
            </svg>
          </summary>
          <div class="modal modal--data-list dropshadow--dark">
            <ul class="data-list">
              <li class="data-list__item">
                <button type="button" class="data-list__button">
                  MBARI
                </button>
              </li>
              <li class="data-list__item">
                <button type="button" class="data-list__button">
                  WoRMS
                </button>
              </li>
            </ul>
          </div>
        </details>
      </label>
    </li>
  </ul>
  <p class="search-box__submit">
    <button type="submit" class="button button--tertiary button--round search-box__button">
      <svg aria-label="Search" class="icon icon--small" width="24" height="24">
        <use xlink:href="#icon-search"></use>
      </svg>
    </button>
  </p>
</form>
```

</div>




