# Media Block

Classes for creating media blocks. Media blocks are block with an image and text
sitting to the right or left. These can easily be created using floats and creating
a new block formatting context on the content.

## Installation

```
bower install fonzie-media-block
```

## Usage

```scss
@include fz-MediaBlock;
```

```html
<div class="fz-mediaBlock fz-mediaBlock--reverse">
  <img class="fz-mediaBlock-image">
  <div class="fz-mediaBlock-body">
    Some Text
  </div>
</div>
```