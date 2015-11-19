# noths-staple-less

A collection of useful LESS mixins for notonthehighstreet.com

## Installation

`npm install notonthehighstreet/noths-staple-less`

## Example

```CSS
import "noths-staple-less";

// Cross browser rotation
.rotated {
  #utils > .rotate(20deg);
}

.long-text {
  #utils > .ellipsis;
}

.pad_with_gutter(@multiple:1){
  #staple > .pad_with_gutter(10px, @multiple);
}

```
