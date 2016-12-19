# tachyons-modular-typography 1.0.0



#### Stats

414 | 6 | 10
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-modular-typography
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-modular-typography
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-modular-typography.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-modular-typography";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons-modular-typography@1.0.0/css/tachyons-modular-typography.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-modular-typography">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*

   TYPOGRAPHY
   http://tachyons.io/docs/typography/measure/

   Media Query Extensions:
     -ns = not-small
     -m  = medium
     -l  = large

*/
/* Measure is limited to ~66 characters */
.measure { max-width: 30em; }
/* Measure is limited to ~80 characters */
.measure-wide { max-width: 34em; }
/* Measure is limited to ~45 characters */
.measure-narrow { max-width: 20em; }
/* Book paragraph style - paragraphs are indented with no vertical spacing. */
.indent { text-indent: 1em; margin-top: 0; margin-bottom: 0; }
.small-caps { font-variant: small-caps; }
/* Combine this class with a width to truncate text (or just leave as is to truncate at width of containing element. */
.truncate { white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
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

