---
layout: default

colorsLight:

  - label: Demersal Gray
    id: demersal-gray
    value: '#6D6C90'

  - label: Pelagic Gray
    id: pelagic-gray
    value: '#AEAEC2'

  - label: Salt Marsh Gray
    id: salt-marsh-gray
    value: '#E8E8ED'

  - label: Sea Salt Gray
    id: sea-salt-gray
    value: '#F7F7F9'

  - label: White
    id: white
    value: '#FFFFFF'

  - label: Benthos Blue
    id: benthos-blue
    value: '#001252'

  - label: Ultramarine Blue
    id: ultramarine-blue
    value: '#557AFF'

  - label: Bay Blue
    id: bay-blue
    value: '#88A2FF'

  - label: Lagoon Blue
    id: lagoon-blue
    value: '#BBCAFF'

  - label: Littoral Blue
    id: littoral-blue
    value: '#F0F3FF'

  - label: Photic Green
    id: photic-green
    value: '#26BF9B'

  - label: Seafoam Green
    id: seafoam-green
    value: '#E4FFF8'

  - label: Snapper Red
    id: snapper-red
    value: '#FF6464'

  - label: Coral Red
    id: coral-red
    value: '#FEE9E9'

colorsDark:

  - label: Hado Gray
    id: hado-gray
    value: '#151928'

  - label: Abyss Gray
    id: abyss-gray
    value: '#212841'

  - label: Aphotic Blue
    id: aphotic-blue
    value: '#5264A3'

---

<h1>Color</h1>

<div class="components-preview components-preview--grid">

  {% for color in page.colorsLight %}
  <div class="components-swatch" style="--color: var(--{{ color.id }})">
    {{ color.label }}
    <br />
    <code>{{ color.value }}</code>
    <br />
    <code>--{{ color.id }}</code>
  </div>
  {% endfor %}

</div>

<div class="components-code" markdown="1">
</div>

<div class="components-preview components-preview--grid">

  {% for color in page.colorsDark %}
  <div class="components-swatch" style="--color: var(--{{ color.id }})">
    {{ color.label }}
    <br />
    <code>{{ color.value }}</code>
    <br />
    <code>--{{ color.id }}</code>
  </div>
  {% endfor %}

</div>

<div class="components-code" markdown="1">

{% comment %}
```css
{% for color in page.colorsLight -%}
--{{ color.id }}: {{ color.value }};
{% endfor %}
```

```css
--benthos-blue: #001252;
--abyss-gray: #212841;
--salt-marsh-gray: #E8E8ED;
--snapper-red: #FF6464;
--ultramarine-blue: #557AFF;
```
{% endcomment %}

</div>
