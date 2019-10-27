# layouts - レイアウト

## 概要

**layouts**は***otogi.css***で使用できるレイアウトパターンです。

## layer - レイヤー

### 概要

`layer`は***otogi.css***の基本レイアウトの一つです。

`layer`はペイントソフトのレイヤーのように画面を重ね合わせることができます。

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

また`layer`はネストすることもできます。

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

### カスタマイズ

デフォルトの最大レイヤー数は20です。

`$layer-max-layer-count`の値を変更することで最大レイヤー数を変更できます。

```stylus
$layer-max-layer-count = 100
```


## grid - グリッド

### 概要

`grid`は[flex](https://developer.mozilla.org/ja/docs/Web/CSS/flex)ベースのレイアウトです。

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

### カスタマイズ

デフォルトの設定では横幅12分割です。

`$grid-column-count`の値を変更することで分割数を変更できます。

```stylus
$grid-column-count = 24
```
