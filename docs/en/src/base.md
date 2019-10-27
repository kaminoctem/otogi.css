# base

## Overview

**base** is ***otogi.css*** base components.

## normalize

### Overview

[normalize.css](https://necolas.github.io/normalize.css/) rewritten with stylus.

## initialize

### Overview

Based on `normalize`, each element is initialized to further optimize to *** otogi.css ***.

### helpers

### Overview

It is a helper component when placing each component in *** otogi.css ***.

#### helpers - color

You can set the text color and background color of the element.

```html
<!-- 文字色 -->
<div class="forecolor-success"></div>
<!-- 背景色 -->
<div class="backcolor-warning"></div>
```

#### helpers - typography

set typography property.

```html
<!-- italic -->
<div class="is-italic"></div>
<!-- oblique -->
<div class="is-oblique"></div>
<!-- capitalized [e.g. otogi → Otogi] -->
<div class="is-capitalized"></div>
<!-- lowercase [e.g. OTOGI → otogi] -->
<div class="is-lowercase"></div>
<!-- uppercase [e.g. otogi → OTOGI] -->
<div class="is-uppercase"></div>
```

#### helpers - spacing

You can change the element's margin and padding.

Set a value between 01 and 09 or 1 to 9.

```html
<!-- padding: 0.1em -->
<div class="padding-01"></div>
<!-- padding-top: 0.9em -->
<div class="padding-top-09"></div>
<!-- margin: 1em -->
<div class="margin-1"></div>
<!-- margin-top: 1em -->
<div class="margin-bottom-1"></div>
```

#### helpers - sizing

You can change the size of the element. Set a value between 1 and 400.

***otogi.css*** basically the size is set in width.

```html
<!-- width10% -->
<div class="width-10"></div>
<!-- height30% [optional] -->
<div class="height-30"></div>
```

#### helpers - coordinate

You can change the coordinates of an element.

The coordinates are set with a value from 1 to 400 with the upper left as the base point.

```html
<!-- plus y-axis -->
<div class="y-plus-35"></div>
<!-- minus y-axis -->
<div class="y-minus-10"></div>
<!-- plus x-axis -->
<div class="x-plus-35"></div>
<!-- minus x-axis -->
<div class="x-minus-10"></div>
```

#### helpers - other

```html
<!-- marginless -->
<div class="is-marginless"></div>
<!-- paddingless -->
<div class="is-paddingless"></div>
<!-- text unselectable -->
<div class="is-unselectable"></div>
```
