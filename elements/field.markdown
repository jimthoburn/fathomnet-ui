---
layout: pattern
title: Field
---

<h1>Field</h1>

<div class="components-preview">

<label class="field field--has-placeholder">
  <span class="field__label">First name</span>
  <input
    type="text"
    class="field__input"
    placeholder="First name" />
</label>

</div>

<div class="components-code" markdown="1">

```html
<label class="field field--has-placeholder">
  <span class="field__label">First name</span>
  <input
    type="text"
    placeholder="First name"
    class="field__input"
    />
</label>
```

</div>




<div class="components-preview">

<label class="field field--has-placeholder field--has-icon">
  <span class="field__label">First name</span>
  <input
    type="text"
    value="First name"
    placeholder="First name"
    readonly
    class="field__input"
    />
  <svg class="icon"><use xlink:href="#icon-lock"></use></svg>
</label>

</div>

<div class="components-code" markdown="1">

```html
<label class="field field--has-placeholder field--has-icon">
  <span class="field__label">First name</span>
  <input
    type="text"
    value="First name"
    placeholder="First name"
    readonly
    class="field__input"
    />
  <svg class="icon field__icon"><use xlink:href="#icon-lock"></use></svg>
</label>
```

</div>



