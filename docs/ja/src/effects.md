# effects - エフェクト

## 概要

***otogi.css***で使用できるエフェクトです。

**effects**は**animations**と組み合わせて使用することができます。

エフェクトを徐々に適用する場合は`animation chiaroscuro-5-cresc`のように`-cresc`を、

徐々にはずす場合は`animation chiaroscuro-5-decresc`のように`-decresc`を設定します。

## chiaroscuro - キアロスクーロ

### 概要

`chiaroscuro`は要素に[キアロスクーロ](https://ja.wikipedia.org/wiki/%E3%82%AD%E3%82%A2%E3%83%AD%E3%82%B9%E3%82%AF%E3%83%BC%E3%83%AD)のような効果を適用するフィルターエフェクトです。

`chiaroscuro-5`のように1~10のレベルで設定します。

```html
<div class="background chiaroscuro-5">
  <img class="background-image" src="image/background.png" alt="background" />
<div>
```

## gaussianblur - ガウスぼかし

### 概要

`gaussianblur`は要素に[ガウスぼかし](https://ja.wikipedia.org/wiki/%E3%82%AC%E3%82%A6%E3%82%B7%E3%82%A2%E3%83%B3%E3%81%BC%E3%81%8B%E3%81%97)を適用するフィルターエフェクトです。

`gaussianblur-5`のように1~10のレベルで設定します。

```html
<div class="character gaussianblur-5">
  <img class="character-image" src="image/character.png" alt="character" />
<div>
```

## grisaille - グリザイユ

### 概要

`grisaille`は要素に[グリザイユ](https://ja.wikipedia.org/wiki/%E3%82%B0%E3%83%AA%E3%82%B6%E3%82%A4%E3%83%A6)のような効果を適用するフィルターエフェクトです。

セピアの`grisaille-sepia`またはグレースケールの`grisaille-gray`を設定します。

```html
<div class="background grisaille-sepia">
  <img class="background-image" src="image/background.png" alt="background" />
<div>
```

## negative - 補色

### 概要

`negative`は要素の色を[補色](https://ja.wikipedia.org/wiki/%E8%A3%9C%E8%89%B2)に変更するフィルターエフェクトです。

`negative`を設定します。

```html
<div class="background negative">
  <img class="background-image" src="image/background.png" alt="background" />
<div>
```

## translucent - 半透明

### 概要

`translucent`は要素を半透明に変更するフィルターエフェクトです。

`translucent-5`のように1~10のレベルで設定します。

```html
<div class="character translucent-5">
  <img class="character-image" src="image/character.png" alt="character" />
<div>
```
