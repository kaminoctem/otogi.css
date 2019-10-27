# スタート!

## インストール

### npm

```
npm install otogi.css
```

### Yarn

```
yarn add otogi.css
```

## ベーシックな使い方

### ステップ1: ***otogi.css***👸🏻👘を追加する

`<head>`タグの下に`<link rel="stylesheet" href="otogi.min.css" />`を追加します。

```html
<html>
  <head>
    <link rel="stylesheet" href="otogi.min.css" />
  </head>
  <body>
  </body>
</html>
```

### ステップ2: `otogiroot`🧶を追加する

`<body>`タグの直下に`<div class="otogiroot">`を追加します。

```html
<html>
  <head>
    <link rel="stylesheet" href="otogi.min.css" />
  </head>
  <body>
    <div class="otogiroot">
    </div>
  </body>
</html>
```

### ステップ3: レイヤーを追加する

`<div class="layer-folder">`と`<div class="layer-{order}">`を追加します。

```html
<html>
  <head>
    <link rel="stylesheet" href="otogi.min.css" />
  </head>
  <body>
    <div class="otogiroot">
      <div class="layer-folder">
        <div class="layer-1">
        </div>
        <div class="layer-2">
        </div>
        <div class="layer-3">
        </div>
      </div>
    </div>
  </body>
</html>
```

### ステップ4: レイヤーにコンポーネントを追加!

```html
<html>
  <head>
    <link rel="stylesheet" href="otogi.min.css" />
  </head>
  <body>
    <div class="otogiroot">
      <div class="layer-folder">
        <div class="layer-1">
          <!-- 背景 -->
          <div class="backgroudlayer">
            <div class="background">
              <img class="background-image" src="background.png" alt="background-image" />
            </div>
          </div>
        </div>
        <div class="layer-2">
          <!-- キャラクター -->
          <div class="characterlayer">
            <div class="character">
              <img class="character-image" src="character.png" alt="character-image" />
            </div>
          </div>
        </div>
        <div class="layer-3">
          <!-- メッセージウィンドウ -->
          <div class="messagewindowlayer">
            <div class="messagewindow">
              <div class="messagewindow-header">
                <div class="padding-left-2">
                  <label class="label">キャラクター名</label>
                </div>
              </div>
              <div class="messagewindow-body">
                  <div class="row">
                    <div class="column-2">
                      <div class="messagewindow-character width-110">
                        <img class="messagewindow-character-image" src="character.png" alt="character-image" />
                      </div>
                    </div>
                    <div class="column-10">
                      <div class="messagewindow-message">
                        メッセージです（　＾ω＾）・・・
                      </div>
                    </div>
                  </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
```

