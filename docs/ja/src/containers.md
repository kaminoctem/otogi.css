# containers - コンテナー

## otogiroot - otogi.cssルートコンテナー

### 概要

`otogiroot`は***otogi.css***を使用する上でのルートコンテナーです。

`otogiroot`は画面のアスペクト比を固定します。

`otogiroot`は必ず`body`直下に配置してください。

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

### カスタマイズ

デフォルトのアスペクト比は16:9です。

`$otogiroot-aspect-ratio-x`および`$otogiroot-aspect-ratio-y`の値を変更することでアスペクト比を変更できます。

```stylus
$otogiroot-aspect-ratio-x = 4
$otogiroot-aspect-ratio-y = 3
```
