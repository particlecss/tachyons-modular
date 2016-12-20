# tachyons-modular-display 1.0.0

obile-first single purpose display utilities from Tachyons.

#### Stats

369 | 12 | 13
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-modular-display
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
@import "tachyons-modular-display";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons-modular-display@1.0.0/build/build.min.css" />
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

   DISPLAY
   Docs: http://tachyons.io/docs/layout/display

   Base:
    d = display

   Modifiers:
    n     = none
    b     = block
    ib    = inline-block
    it    = inline-table
    t     = table
    tc    = table-cell
    tr    = table-row
    tcol  = table-column
    tcolg = table-column-group

   Media Query Extensions:
     -ns = not-small
     -m  = medium
     -l  = large

*/
.dn { display: none; }
.di { display: inline; }
.db { display: block; }
.dib { display: inline-block; }
.dit { display: inline-table; }
.dt { display: table; }
.dtc { display: table-cell; }
.dt-row { display: table-row; }
.dt-row-group { display: table-row-group; }
.dt-column { display: table-column; }
.dt-column-group { display: table-column-group; }
/*
  This will set table to full width and then
  all cells will be equal width
*/
.dt--fixed { table-layout: fixed; width: 100%; }
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

