# tachyons-modular-type-scale 1.0.0



#### Stats

380 | 10 | 8
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-modular-type-scale
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-modular-type-scale
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-modular-type-scale.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-modular-type-scale";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons-modular-type-scale@1.0.0/css/tachyons-modular-type-scale.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-modular-type-scale">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*

   TYPE SCALE
   Docs: http://tachyons.io/docs/typography/scale/

   Base:
    f = font-size

   Modifiers
     1 = 1st step in size scale
     2 = 2nd step in size scale
     3 = 3rd step in size scale
     4 = 4th step in size scale
     5 = 5th step in size scale
     6 = 6th step in size scale

   Media Query Extensions:
     -ns = not-small
     -m  = medium
     -l  = large
*/
/*
 * For Hero/Marketing Titles
 *
 * These generally are too large for mobile
 * so be careful using them on smaller screens.
 * */
.f-6, .f-headline { font-size: 6rem; }
.f-5, .f-subheadline { font-size: 5rem; }
/* Type Scale */
.f1 { font-size: 3rem; }
.f2 { font-size: 2.25rem; }
.f3 { font-size: 1.5rem; }
.f4 { font-size: 1.25rem; }
.f5 { font-size: 1rem; }
.f6 { font-size: .875rem; }
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

