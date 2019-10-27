# base - ベース

## 概要

**base**は***otogi.css***の基礎コンポーネントです。

## normalize

### 概要

[normalize.css](https://necolas.github.io/normalize.css/)をstylusで書き直したものです。

## initialize

### 概要

`normalize`をベースに、さらに***otogi.css***に最適化するために各要素を初期化します。

### helpers

### 概要

***otogi.css***で各コンポーネントを配置する際のヘルパーコンポーネントです。

#### helpers - color

要素の文字色、背景色を設定することができます。

```html
<!-- 文字色 -->
<div class="forecolor-success"></div>
<!-- 背景色 -->
<div class="backcolor-warning"></div>
```

#### helpers - typography

文字のプロパティを変更できます。

```html
<!-- イタリック -->
<div class="is-italic"></div>
<!-- 斜体 -->
<div class="is-oblique"></div>
<!-- キャピタライズ [e.g. otogi → Otogi] -->
<div class="is-capitalized"></div>
<!-- 小文字化 [e.g. OTOGI → otogi] -->
<div class="is-lowercase"></div>
<!-- 大文字化 [e.g. otogi → OTOGI] -->
<div class="is-uppercase"></div>
```

#### helpers - spacing

要素のmarginおよびpaddingを変更できます。01~09または1~9の値で設定します。

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

要素のサイズを変更できます。1~400の値で設定します。

***otogi.css***では横幅でのサイジングが基本です。

```html
<!-- 横10% -->
<div class="width-10"></div>
<!-- 縦30% -->
<div class="height-30"></div>
```

#### helpers - coordinate

要素の座標を変更できます。座標は左上が基点で1~400の値で設定します。

```html
<!-- y軸プラス -->
<div class="y-plus-35"></div>
<!-- y軸マイナス -->
<div class="y-minus-10"></div>
<!-- x軸プラス -->
<div class="x-plus-35"></div>
<!-- x軸マイナス -->
<div class="x-minus-10"></div>
```

#### helpers - other

```html
<!-- マージンなし -->
<div class="is-marginless"></div>
<!-- パディングなし -->
<div class="is-paddingless"></div>
<!-- 文字列の選択不可 -->
<div class="is-unselectable"></div>
```
