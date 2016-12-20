# tachyons-modular-media-queries 1.0.0



#### Stats

367 | 0 | 0
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-modular-media-queries
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
@import "tachyons-modular-media-queries";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons-modular-media-queries@1.0.0/build/build.min.css" />
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

  CUSTOM MEDIA QUERIES

  Media query values can be changed to fit your own content.
  There are no magic bullets when it comes to media query width values.
  They should be declared in em units - and they should be set to meet
  the needs of your content. You can also add additional media queries,
  or remove some of the existing ones.

  These media queries can be referenced like so:

  @media (--breakpoint-not-small) {
    .medium-and-larger-specific-style {
      background-color: red;
    }
  }

  @media (--breakpoint-medium) {
    .medium-screen-specific-style {
      background-color: red;
    }
  }

  @media (--breakpoint-large) {
    .large-and-larger-screen-specific-style {
      background-color: red;
    }
  }

*/
/* Media Queries */
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

