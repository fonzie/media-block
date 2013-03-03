# Media Block

Classes for creating media blocks. Media blocks are block with an image and text
sitting to the right or left. These can easily be created using floats and creating
a new block formatting context on the content.

## Installation

```
fonzie install media-block
```

## Usage

```scss
@import "media-block";
```

```html
<div class="media-block">
  <img class="media-block__image">
  <div class="media-block__body">
    Some Text
  </div>
</div>
```