# tachyons-modular-border-radius 1.0.0

Border radius CSS module for Tachyons.

#### Stats

355 | 11 | 15
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-modular-border-radius
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
@import "tachyons-modular-border-radius";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons-modular-border-radius@1.0.0/build/build.min.css" />
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

   BORDER RADIUS
   Docs: http://tachyons.io/docs/themes/border-radius/

   Base:
     br   = border-radius

   Modifiers:
     0    = 0/none
     1    = 1st step in scale
     2    = 2nd step in scale
     3    = 3rd step in scale
     4    = 4th step in scale

   Literal values:
     -100 = 100%
     -pill = 9999px

   Media Query Extensions:
     -ns = not-small
     -m  = medium
     -l  = large

*/
.br0 { border-radius: 0; }
.br1 { border-radius: .125rem; }
.br2 { border-radius: .25rem; }
.br3 { border-radius: .5rem; }
.br4 { border-radius: 1rem; }
.br-100 { border-radius: 100%; }
.br-pill { border-radius: 9999px; }
.br--bottom { border-top-left-radius: 0; border-top-right-radius: 0; }
.br--top { border-bottom-left-radius: 0; border-bottom-right-radius: 0; }
.br--right { border-top-left-radius: 0; border-bottom-left-radius: 0; }
.br--left { border-top-right-radius: 0; border-bottom-right-radius: 0; }
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

