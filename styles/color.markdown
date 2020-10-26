---
layout: default

colorsLight:

  - label: Demersal Gray
    id: color-demersal-gray
    value: '#6D6C90'

  - label: Pelagic Gray
    id: color-pelagic-gray
    value: '#AEAEC2'

  - label: Salt Marsh Gray
    id: color-salt-marsh-gray
    value: '#E8E8ED'

  - label: Sea Salt Gray
    id: color-sea-salt-gray
    value: '#F7F7F9'

  - label: White
    id: color-white
    value: '#FFFFFF'

  - label: Benthos Blue
    id: color-benthos-blue
    value: '#001252'

  - label: Ultramarine Blue
    id: color-ultramarine-blue
    value: '#557AFF'

  - label: Bay Blue
    id: color-bay-blue
    value: '#88A2FF'

  - label: Lagoon Blue
    id: color-lagoon-blue
    value: '#BBCAFF'

  - label: Littoral Blue
    id: color-littoral-blue
    value: '#F0F3FF'

  - label: Photic Green
    id: color-photic-green
    value: '#26BF9B'

  - label: Seafoam Green
    id: color-seafoam-green
    value: '#E4FFF8'

  - label: Snapper Red
    id: color-snapper-red
    value: '#FF6464'

  - label: Coral Red
    id: color-coral-red
    value: '#FEE9E9'

colorsDark:

  - label: Hado Gray
    id: color-hado-gray
    value: '#151928'

  - label: Abyss Gray
    id: color-abyss-gray
    value: '#212841'

  - label: Aphotic Blue
    id: color-aphotic-blue
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

</div>
