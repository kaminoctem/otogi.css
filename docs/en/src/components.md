# components

## Overview

**components** is a component that can be used in ***otogi.css***.

## background

### Overview

`background` is one of the basic components of *** otogi.css ***.

Set the background on the screen.

`background` is used in combination with *layouts* ` layer`.

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

## character

### Overview

`character` is one of the basic components of *** otogi.css ***.

Set the character on the screen.

`character` is used in combination with `layer` in *layouts*.

To adjust the size, use `width` in *helpers* of *base*.

Coordinate adjustments use `x-plus- {percentage}`, `x-minus- {percentage}`, `y-plus- {percentage}` and `y-minus- {percentage } `in  *helpers* of *base*.

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

## messagewindow

### Overview

`messagewindow` is one of the basic components of *** otogi.css ***.

Set the message window on the screen.

`messagewindow` is used in combination with `layer` in *layouts*.

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

If you want the message window to fill the screen, set `is-fullheight` like` messagewindow is-fullheight`.

If you want a margin, set `is-fullheight-with-margin`.

## choice

### Overview

Set the choices on the screen.

`choice` is used in combination with `messagewindow` in *components*.

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
