# tachyons-modular-rotations 1.0.0



#### Stats

165 | 7 | 14
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-modular-rotations
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-modular-rotations
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-modular-rotations.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-modular-rotations";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons-modular-rotations@1.0.0/css/tachyons-modular-rotations.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-modular-rotations">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*

   ROTATIONS

*/
.rotate-45 { -webkit-transform: rotate( 45deg ); transform: rotate( 45deg ); }
.rotate-90 { -webkit-transform: rotate( 90deg ); transform: rotate( 90deg ); }
.rotate-135 { -webkit-transform: rotate( 135deg ); transform: rotate( 135deg ); }
.rotate-180 { -webkit-transform: rotate( 180deg ); transform: rotate( 180deg ); }
.rotate-225 { -webkit-transform: rotate( 225deg ); transform: rotate( 225deg ); }
.rotate-270 { -webkit-transform: rotate( 270deg ); transform: rotate( 270deg ); }
.rotate-315 { -webkit-transform: rotate( 315deg ); transform: rotate( 315deg ); }
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
