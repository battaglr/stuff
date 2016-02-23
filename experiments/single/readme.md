# Single

Single-responsibility classes for CSS.

## Overview

A highly experimental library of single-responsibility classes inspired mostly
by [Atomic CSS](http://acss.io/)’s architecture and [Emmet](http://emmet.io/)’s
syntax.

- If you know [Emmet](http://emmet.io/) you already know *Single*.
- The `!important` declaration ensures applicability.
- ~12.88 kB (*compiled, minified and gzipped*).

*Please, remember that this is just an experiment. If you want to use something
like this in production try [Atomic CSS](http://acss.io/).*

## Usage

```html
<div class="BxS-bB W-50 P-20 MX-a">
  <span class="D-b FW-700"> ... </span>
  ...
</div>
```

## Available classes

##### `width`

- `W-a` - `width: auto;`
- `W-<0-100>` - `width: <0-100%>;`

##### `height`

- `H-a` - `height: auto;`
- `H-<0-100>` - `height: <0-100%>;`

##### `padding`

- `P-<0-100>` - `padding: <0-100px>;`
- `PX-<0-100>` - `padding-right: <0-100px>; padding-left: <0-100px>;`
- `PY-<0-100>` - `padding-top: <0-100px>; padding-bottom: <0-100px>;`
- `PT-<0-100>` - `padding-top: <0-100px>;`
- `PR-<0-100>` - `padding-right: <0-100px>;`
- `PB-<0-100>` - `padding-bottom: <0-100px>;`
- `PL-<0-100>` - `padding-left: <0-100px>;`

##### `margin`

- `M-<0-100>` - `margin: <0-100px>;`
- `M-a` - `margin: auto;`
- `MX-<0-100>` - `margin-right: <0-100px>; margin-left: <0-100px>;`
- `MX-a` - `margin-right: auto; margin-left: auto;`
- `MY-<0-100>` - `margin-top: <0-100px>; margin-bottom: <0-100px>;`
- `MT-<0-100>` - `margin-top: <0-100px>;`
- `MR-<0-100>` - `margin-right: <0-100px>;`
- `MR-a` - `margin-right: auto;`
- `MB-<0-100>` - `margin-bottom: <0-100px>;`
- `ML-<0-100>` - `margin-left: <0-100px>;`
- `ML-a` - `margin-left: auto;`

##### `border-width`

- `BdW-n` - `border-width: none;`
- `BdXW-n` - `border-right-width: none; border-left-width: none;`
- `BdYW-n` - `border-top-width: none; border-bottom-width: none;`
- `BdTW-n` - `border-top-width: none;`
- `BdRW-n` - `border-right-width: none;`
- `BdBW-n` - `border-bottom-width: none;`
- `BdLW-n` - `border-left-width: none;`

##### `box-sizing`

- `BxS-cB` - `box-sizing: content-box;`
- `BxS-bB` - `box-sizing: border-box;`

##### `display`

- `D-i` - `display: inline;`
- `D-b` - `display: block;`
- `D-iB` - `display: inline-block;`
- `D-tb` - `display: table;`
- `D-tbR` - `display: table-row;`
- `D-tbC` - `display: table-cell;`

##### `float`

- `Fl-r` - `float: right;`
- `Fl-l` - `float: left;`
- `Fl-n` - `float: none;`

##### `clear`

- `Cl-r` - `clear: right;`
- `Cl-l` - `clear: left;`
- `Cl-b` - `clear: both;`
- `Cl-n` - `clear: none;`

##### `position`

- `Pos-s` - `position: static;`
- `Pos-r` - `position: relative;`
- `Pos-a` - `position: absolute;`
- `Pos-f` - `position: fixed;`

##### `top`

- `T-<0-100>` - `top: <0-100px>;`

##### `right`

- `R-<0-100>` - `right: <0-100px>;`

##### `bottom`

- `B-<0-100>` - `bottom: <0-100px>;`

##### `left`

- `L-<0-100>` - `left: <0-100px>;`

##### `z-index`

- `Z-<0-100>` - `z-index: <0-100px>;`

##### `font-weight`

- `FW-100` - `font-weight: 100;`
- `FW-200` - `font-weight: 200;`
- `FW-300` - `font-weight: 300;`
- `FW-400` - `font-weight: 400;`
- `FW-500` - `font-weight: 500;`
- `FW-600` - `font-weight: 600;`
- `FW-700` - `font-weight: 700;`
- `FW-800` - `font-weight: 800;`
- `FW-900` - `font-weight: 900;`

##### `font-size`

- `FZ-<0-100>` - `font-size: <0-100px>;`

##### `cursor`

- `Cur-a` - `cursor: auto;`
- `Cur-d` - `cursor: default;`
- `Cur-p` - `cursor: pointer;`
- `Cur-t` - `cursor: text;`

##### Others

- `Cf` - *Clearfix*.

## Motivation

*Single* was an attempt to determinate if a statically generated library
using the architectural principles of [Atomic CSS](http://acss.io/) would be
practical to use or develop. Apparently it wouldn’t; at least not with the
level of flexibility that [Atomic CSS](http://acss.io/) has, and an attempt
to emulate it will result in significantly bloated stylesheets with many
classes that will never be used.

This, by no means, implies that utility or helper classes are impractical,
just that they need to be defined and used thoughtfully.

## License

Do whatever you want with this, it’s public domain.
