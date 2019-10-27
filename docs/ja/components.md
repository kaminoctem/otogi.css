# components - コンポーネント

## 概要

**components**は***otogi.css***で使用できるコンポーネントです。

## background - 背景

### 概要

`background`は***otogi.css***の基本コンポーネントの一つです。

背景を画面に設定します。

`background`は*layouts*の`layer`と組み合わせて使用します。

```html
<div class="otogiroot">
  <div class="layer-folder">
    <div class="layer-1">
      <div class="backgroudlayer">
        <div class="background">
          <img class="background-image" src="images/background.png" alt="background-image" />
        </div>
      </div>
    </div>
    <div class="layer-2">
    </div>
    <div class="layer-3">
    </div>
  </div>
</div>
```

## character - キャラクター

### 概要

`character`は***otogi.css***の基本コンポーネントの一つです。

画面にキャラクターを配置します。

`character`は*layouts*の`layer`と組み合わせて使用します。

サイズの調整は*base*の*helpers*にある`width`を使用します。

座標の調整は*base*の*helpers*にある`x-plus-{percentage}`、`x-minus-{percentage}`、`y-plus-{percentage}`および`y-minus-{percentage}`を使用します。

```html
<div class="otogiroot">
  <div class="layer-folder">
    <div class="layer-1">
    </div>
    <div class="layer-2">
      <div class="characterlayer">
        <div class="character width-40 x-plus-30">
          <img class="character-image" src="images/character-1.png" alt="character-1-image" />
        </div>
        <div class="character width-60">
          <img class="character-image" src="images/character-2.png" alt="character-2-image" />
        </div>
      </div>
    </div>
    <div class="layer-3">
    </div>
  </div>
</div>
```

## messagewindow - メッセージウィンドウ

### 概要

`messagewindow`は***otogi.css***の基本コンポーネントの一つです。

画面にキャラクターを配置します。

`messagewindow`は*layouts*の`layer`と組み合わせて使用します。

```html
<div class="otogiroot">
  <div class="layer-folder">
    <div class="layer-1">
    </div>
    <div class="layer-2">
    </div>
    <div class="layer-3">
      <div class="messagewindowlayer">
        <div class="messagewindow">
          <div class="messagewindow-body">
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
```

画面いっぱいにメッセージウィンドウを表示する場合は`is-fullheight`を`messagewindow is-fullheight`のように設定します。

マージンを設ける場合は`is-fullheight-with-margin`を設定します。

## choice - 選択肢

### 概要

画面に選択肢を配置します。

`choice`は*components*の`messagewindow`と組み合わせて使用します。

```html
<div class="otogiroot">
  <div class="layer-folder">
    <div class="layer-1">
    </div>
    <div class="layer-2">
    </div>
    <div class="layer-3">
      <div class="messagewindowlayer">
        <div class="messagewindow is-fullheight-with-margin">
          <div class="messagewindow-body">
            <div class="choices margin-1">
              <div class="choice">
                <button>choice1</button>
              </div>
              <div class="choice">
                <button>choice2</button>
              </div>
              <div class="choice">
                <button>choice3</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
```
