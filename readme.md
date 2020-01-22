# stylelint-config-order

Stylelint config that sorts related property declarations by grouping together following the order:

- Layout Properties (z-index, position, float, clear, display)
- Box Model Properties (width, height, margin, padding)
- Visual Properties (background, border)
- Typography Properties (color, font-size, font-family, text-align)
- Transform Properties (transform, perspective)
- Misc Properties (cursor, overflow)


## Install

```
$ npm install @puredazzle/stylelint-config-order --save-dev
```


## Usage

Add the following to your [Stylelint config](https://stylelint.io/user-guide/configuration/):

```json
{
	"extends": "@puredazzle/stylelint-config-order"
}
```
