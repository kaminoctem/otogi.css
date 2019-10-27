# layouts

## Overview

**layouts** is a layout pattern that can be used in ***otogi.css***.

## layer

### Overview

`layer` is one of the basic layouts of ***otogi.css***.

`layer` can superimpose the screen like a layer of paint software.

```html
<div class="layer-folder">
  <div class="layer-1">
  </div>
  <div class="layer-2">
  </div>
  <div class="layer-3">
  </div>
</div>
```

`layer` can also be nested.

```html
<div class="layer-folder">
  <div class="layer-1">
    <div class="layer-folder">
      <div class="layer-1">
      </div>
      <div class="layer-2">
      </div>
    </div>
  </div>
  <div class="layer-2">
    <div class="layer-folder">
      <div class="layer-1">
      </div>
      <div class="layer-2">
      </div>
    </div>
  </div>
</div>
```

### Customization

The default maximum number of layers is 20.

You can change the maximum number of layers by changing the value of `$ layer-max-layer-count`.

```stylus
$layer-max-layer-count = 100
```

## grid

### Overview

`grid` is a layout based on [flex](https://developer.mozilla.org/en-US/docs/Web/CSS/flex).

```html
<div class="grid">
  <div class="row">
    <div class="column-2">
    </div>
    <div class="column-8">
    </div>
    <div class="column-2">
    </div>
  </div>
</div>
```

### Customization

The default setting is 12 horizontal widths.

You can change the number of divisions by changing the value of `$ grid-column-count`.

```stylus
$grid-column-count = 24
```
