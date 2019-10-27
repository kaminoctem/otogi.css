# containers

## otogiroot

### Overview

`otogiroot` is a root container for using ***otogi.css***.

`otogiroot` fixes the screen aspect ratio.

Make sure to place `otogiroot` directly under` body`.

```html
<html>
  <head>
  </head>
  <body>
    <div class="otogiroot">
    </div>
  </body>
</html>
```

### Customization

The default aspect ratio is 16: 9.

You can change the aspect ratio by changing the values ​​of `$otogiroot-aspect-ratio-x` and `$otogiroot-aspect-ratio-y`.

```stylus
$otogiroot-aspect-ratio-x = 4
$otogiroot-aspect-ratio-y = 3
```
