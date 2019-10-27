# Start!

## Installation

### npm

```
npm install otogi.css
```

### Yarn

```
yarn add otogi.css
```

## The Basics

### Step1: Add ***otogi.css***👸🏻👘

add `<link rel="stylesheet" href="otogi.min.css" />` under `<head>`

```html
<html>
  <head>
    <link rel="stylesheet" href="otogi.min.css" />
  </head>
  <body>
  </body>
</html>
```

### Step 2: Add `otogiroot`🧶

add `<div class="otogiroot">` directly under `<body>`.

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

### Step 3: Add layers

add `<div class="layer-folder">` and `<div class="layer-{order}">`.

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

### Step 4: Add components to layers

```html
<html>
  <head>
    <link rel="stylesheet" href="otogi.min.css" />
  </head>
  <body>
    <div class="otogiroot">
      <div class="layer-folder">
        <div class="layer-1">
          <!-- Background -->
          <div class="backgroudlayer">
            <div class="background">
              <img class="background-image" src="background.png" alt="background-image" />
            </div>
          </div>
        </div>
        <div class="layer-2">
          <!-- Character -->
          <div class="characterlayer">
            <div class="character">
              <img class="character-image" src="character.png" alt="character-image" />
            </div>
          </div>
        </div>
        <div class="layer-3">
          <!-- Message Window -->
          <div class="messagewindowlayer">
            <div class="messagewindow">
              <div class="messagewindow-header">
                <div class="padding-left-2">
                  <label class="label">Character Name</label>
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
                        messages...
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

