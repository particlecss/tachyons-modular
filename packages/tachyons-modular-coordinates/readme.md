# tachyons-modular-coordinates 1.0.0

Performance based css module. Use in combination with the position module.

#### Stats

384 | 21 | 24
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-modular-coordinates
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
@import "tachyons-modular-coordinates";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons-modular-coordinates@1.0.0/build/build.min.css" />
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

   COORDINATES
   Docs: http://tachyons.io/docs/layout/position/

   Use in combination with the position module.

   Base:
     top
     bottom
     right
     left

   Modifiers:
     -0  = literal value 0
     -1  = literal value 1
     -2  = literal value 2
     --1 = literal value -1
     --2 = literal value -2

   Media Query Extensions:
     -ns = not-small
     -m  = medium
     -l  = large

*/
.top-0 { top: 0; }
.right-0 { right: 0; }
.bottom-0 { bottom: 0; }
.left-0 { left: 0; }
.top-1 { top: 1rem; }
.right-1 { right: 1rem; }
.bottom-1 { bottom: 1rem; }
.left-1 { left: 1rem; }
.top-2 { top: 2rem; }
.right-2 { right: 2rem; }
.bottom-2 { bottom: 2rem; }
.left-2 { left: 2rem; }
.top--1 { top: -1rem; }
.right--1 { right: -1rem; }
.bottom--1 { bottom: -1rem; }
.left--1 { left: -1rem; }
.top--2 { top: -2rem; }
.right--2 { right: -2rem; }
.bottom--2 { bottom: -2rem; }
.left--2 { left: -2rem; }
.absolute--fill { top: 0; right: 0; bottom: 0; left: 0; }
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

