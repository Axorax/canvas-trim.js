# `canvas-trim`

Trim whitespace from a canvas

## Installation

```terminal
npm i canvas-trim
```

## Usage

```js
canvasTrim(document.querySelector('#myCanvas'));
```

```js
const trimmed = canvasTrim(document.querySelector('#myCanvas'));

trimmed.toBlob(function(blob) {
    console.log(URL.createObjectURL(blob));
}, "image/jpeg", 0.75);
```

**credit: ourcodeworld.com (Carlos Delgado)**

---

[Support me on Patreon](https://www.patreon.com/axorax) - 
[Check out my socials](https://github.com/axorax/socials)
