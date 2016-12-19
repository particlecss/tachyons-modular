# tachyons-modular-tables 1.0.0



#### Stats

356 | 7 | 8
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-modular-tables
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-modular-tables
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-modular-tables.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-modular-tables";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons-modular-tables@1.0.0/css/tachyons-modular-tables.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-modular-tables">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*

  TABLES
  Docs: http://tachyons.io/docs/elements/tables/

*/
/**
 * Dependengies (color variables)
 * TODO: define local variables for colors
 * TODO: formart to stylelint standard
 */
/*

   Tachyons
   COLOR VARIABLES

   Grayscale
   - Solids
   - Transparencies
   Colors

*/
.collapse { border-collapse: collapse; border-spacing: 0; }
.striped--light-silver:nth-child(odd) { background-color: #aaa; }
.striped--moon-gray:nth-child(odd) { background-color: #ccc; }
.striped--light-gray:nth-child(odd) { background-color: #eee; }
.striped--near-white:nth-child(odd) { background-color: #f4f4f4; }
.stripe-light:nth-child(odd) { background-color: rgba( 255, 255, 255, .1 ); }
.stripe-dark:nth-child(odd) { background-color: rgba( 0, 0, 0, .1 ); }
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
