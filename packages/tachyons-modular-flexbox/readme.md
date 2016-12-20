# tachyons-modular-flexbox 1.0.0

Flexbox CSS module for Tachyons.

#### Stats

833 | 38 | 107
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-modular-flexbox
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/particlecss/tachyons-modular.git
```

ssh:
```
git clone git@github.com:particlecss/tachyons-modular.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-modular-flexbox";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/tachyons-modular-flexbox@1.0.0/build/build.min.css" />
```

##### Locally
The built css is located in the `build` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/build/build.min.css">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*

  FLEXBOX

  Media Query Extensions:
   -ns = not-small
   -m  = medium
   -l  = large

*/
.flex { display: -webkit-box; display: -ms-flexbox; display: flex; }
.inline-flex { display: -webkit-inline-box; display: -ms-inline-flexbox; display: inline-flex; }
/* 1. Fix for Chrome 44 bug.
 * https://code.google.com/p/chromium/issues/detail?id=506893 */
.flex-auto { -webkit-box-flex: 1; -ms-flex: 1 1 auto; flex: 1 1 auto; min-width: 0; /* 1 */ min-height: 0; /* 1 */ }
.flex-none { -webkit-box-flex: 0; -ms-flex: none; flex: none; }
.flex-column { -webkit-box-orient: vertical; -webkit-box-direction: normal; -ms-flex-direction: column; flex-direction: column; }
.flex-row { -webkit-box-orient: horizontal; -webkit-box-direction: normal; -ms-flex-direction: row; flex-direction: row; }
.flex-wrap { -ms-flex-wrap: wrap; flex-wrap: wrap; }
.items-start { -webkit-box-align: start; -ms-flex-align: start; align-items: flex-start; }
.items-end { -webkit-box-align: end; -ms-flex-align: end; align-items: flex-end; }
.items-center { -webkit-box-align: center; -ms-flex-align: center; align-items: center; }
.items-baseline { -webkit-box-align: baseline; -ms-flex-align: baseline; align-items: baseline; }
.items-stretch { -webkit-box-align: stretch; -ms-flex-align: stretch; align-items: stretch; }
.self-start { -ms-flex-item-align: start; align-self: flex-start; }
.self-end { -ms-flex-item-align: end; align-self: flex-end; }
.self-center { -ms-flex-item-align: center; -ms-grid-row-align: center; align-self: center; }
.self-baseline { -ms-flex-item-align: baseline; align-self: baseline; }
.self-stretch { -ms-flex-item-align: stretch; -ms-grid-row-align: stretch; align-self: stretch; }
.justify-start { -webkit-box-pack: start; -ms-flex-pack: start; justify-content: flex-start; }
.justify-end { -webkit-box-pack: end; -ms-flex-pack: end; justify-content: flex-end; }
.justify-center { -webkit-box-pack: center; -ms-flex-pack: center; justify-content: center; }
.justify-between { -webkit-box-pack: justify; -ms-flex-pack: justify; justify-content: space-between; }
.justify-around { -ms-flex-pack: distribute; justify-content: space-around; }
.content-start { -ms-flex-line-pack: start; align-content: flex-start; }
.content-end { -ms-flex-line-pack: end; align-content: flex-end; }
.content-center { -ms-flex-line-pack: center; align-content: center; }
.content-between { -ms-flex-line-pack: justify; align-content: space-between; }
.content-around { -ms-flex-line-pack: distribute; align-content: space-around; }
.content-stretch { -ms-flex-line-pack: stretch; align-content: stretch; }
.order-0 { -webkit-box-ordinal-group: 1; -ms-flex-order: 0; order: 0; }
.order-1 { -webkit-box-ordinal-group: 2; -ms-flex-order: 1; order: 1; }
.order-2 { -webkit-box-ordinal-group: 3; -ms-flex-order: 2; order: 2; }
.order-3 { -webkit-box-ordinal-group: 4; -ms-flex-order: 3; order: 3; }
.order-4 { -webkit-box-ordinal-group: 5; -ms-flex-order: 4; order: 4; }
.order-5 { -webkit-box-ordinal-group: 6; -ms-flex-order: 5; order: 5; }
.order-6 { -webkit-box-ordinal-group: 7; -ms-flex-order: 6; order: 6; }
.order-7 { -webkit-box-ordinal-group: 8; -ms-flex-order: 7; order: 7; }
.order-8 { -webkit-box-ordinal-group: 9; -ms-flex-order: 8; order: 8; }
.order-last { -webkit-box-ordinal-group: 100000; -ms-flex-order: 99999; order: 99999; }
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC

