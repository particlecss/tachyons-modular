# Tachyons Modular 
> Modular fork of [Tachyons](https://github.com/trepo/trepo).

This repo contains the following packages:

* `tachyons-modular ` - Functional CSS for humans. The full bundle.
* `tachyons-aspect-ratios` - Css for setting the aspect ratio of an element.
* `tachyons-background-position` - Tachyons module for setting background position of images.
* `tachyons-background-size ` - Background size CSS module for Tachyons.
* `tachyons-border-colors ` - Tachyons border colors. Performance based css module.
* `tachyons-border-radius` - Border radius CSS module for Tachyons.
* `tachyons-border-style` - Border style CSS module for Tachyons.
* `tachyons-border-widths` - Border width CSS module for Tachyons.
* `tachyons-borders` - Performance-first css module for styling borders.
* `tachyons-box-shadow` - Box-shadow CSS module for Tachyons.
* `tachyons-box-sizing` - Css module for a smarter default box-model.
* `tachyons-clears` - Performance based css module.
* `tachyons-code` - Performance based css module.
* `tachyons-colors` - Default CSS color variables for Tachyons.
* `tachyons-coordinates` - Performance based css module.
* `tachyons-debug` - Debug partial for debugging css http://tachyons.io
* `tachyons-debug-children` - Performance based css module.
* `tachyons-debug-grid` - Background grid to help debug alignment issues.
* `tachyons-display` - Mobile-first single purpose display utilities from Tachyons
* `tachyons-flexbox  ` - Flexbox CSS module for Tachyons
* `tachyons-floats` - Single purpose float utilities from Tachyons.
* `tachyons-font-family` - CSS module for setting font-family http://tachyons.io.
* `tachyons-font-style` - CSS module for setting font styles http://tachyons.io.
* `tachyons-font-weight` - Single purpose classes to set font-weight http://tachyons.io.
* `tachyons-forms` - Performance based css module.
* `tachyons-heights` - Single purpose classes to set element height http://tachyons.io
* `tachyons-hovers` - Performance based css module.
* `tachyons-images` - Smarter image defaults from Tachyons.
* `tachyons-letter-spacing` - Letter spacing utilities from Tachyons.
* `tachyons-line-height` - CSS module for setting line-height http://tachyons.io
* `tachyons-links` - CSS module for setting link styles http://tachyons.io.
* `tachyons-lists ` - List utilities from Tachyons.
* `tachyons-max-widths` - CSS module for setting max-widths http://tachyons.io.
* `tachyons-media-queries ` - Performance based css module.
* `tachyons-negative-margins` - Performance based css module.
* `tachyons-nested` - Performance based css module.
* `tachyons-opacity` - Tachyons CSS module for setting opacity http://tachyons.io.
* `tachyons-outlines` - Tachyons module for setting outlines.
* `tachyons-overflow` - CSS module for setting overflow on elements http://tachyons.io
* `tachyons-position` - CSS module for setting position across breakpoints http://tachyons.io.
* `tachyons-rotations` - Tachyons module for setting rotation on elements.
* `tachyons-skins` - Tachyons CSS module for skinning elements http://tachyons.io.
* `tachyons-skins-pseudo` - Skins for hovers and focus states.
* `tachyons-spacing` - CSS module for setting margin and padding across breakpoints http://tachyons.io.
* `tachyons-tables` - Module for styling tables.
* `tachyons-text-align  ` - CSS module for setting the alignment of text across breakpoints http://tachyons.io.
* `tachyons-text-decoration ` - Performance based css module https://tachyons.io.
* `tachyons-text-transform` - CSS module for setting text-transform properties http://tachyons.io.
* `tachyons-type-scale` - CSS module for setting font-sizes across breakpoints http://tachyons.io.
* `tachyons-typography` - CSS utilities for typography http://tachyons.io.
* `tachyons-utilities` - Tachyons utilities module http://tachyons.io.
* `tachyons-vertical-align` - CSS module for setting vertical-align across breakpoints http://tachyons.io.
* `tachyons-visibility` - CSS module for setting visibility on elements http://tachyons.io.
* `tachyons-white-space` - CSS module for controlling white-space http://tachyons.io.
* `tachyons-widths` - CSS module for setting widths http://tachyons.io
* `tachyons-word-break` - A module for doing things with word-break
* `tachyons-z-index` - Tachyons css module for setting z-index on elements
                                                                                     
### Developing
`Tachyons Modular` is a mono-repo managed by [lerna](https://lernajs.io/). To get started clone this repo and run:

````bash
npm install # Installs lerna and dev dependencies
npm run bootstrap # Links packages and installs regular dependencies
````

Development is tracked via Github [projects](https://github.com/trepo/trepo-js/projects) and [issues](https://github.com/trepo/trepo-js/issues).

# TACHYONS

Functional css for humans.

Quickly build and design new UI without writing css.

## Principles

* Everything should be 100% responsive
* Everything should be readable on any device
* Everything should be as fast as possible
* Designing in the browser should be easy
* It should be easy to change any interface or part of an interface without breaking any existing interfaces
* Doing one thing extremely well promotes reusability and reduces repetition
* Documentation helps promote reusability and shared knowledge
* Css shouldn't impede accessibility or the default functionality of Html
* You should send the smallest possible amount of code to the user

## Features

* Mobile-first css architecture
* 490 accessible color combinations
* 8px baseline grid
* Multiple debugging utilities to reduce layout struggles
* Single-purpose class structure
* Optimized for maximum gzip compression
* Lightweight (~14kB)
* Usable across projects
* Growing open source component library
* Works well with plain html, react, ember, angular, rails, and more
* Infinitely nestable responsive grid system
* Built with Postcss

## Getting started

Docs can be found at http://tachyons.io/docs
The modules are generally pretty small and thus quick and easy to read.

### Use the CDN

The quickest and easiest way to start using tachyons is to include a reference
to the minified file in the head of your html file.

You can always grab the latest version with
```html
<link rel="stylesheet" href="https://unpkg.com/tachyons/css/tachyons.min.css">
```
You can also specify a specific version. The latest version is 4.6.1
```html
<link rel="stylesheet" href="https://unpkg.com/tachyons@4.6.1/css/tachyons.min.css">
```

### Local Setup

Clone the repo from github and install dependencies through npm.

```
git clone https://github.com/tachyons-css/tachyons.git
cd tachyons
npm install
```

#### Dev

If you want to just use everything in tachyons/src as a jumping off point and
edit all the code yourself, you can compile all of your wonderful changes by
running

```npm start```

This will output both minified and unminified versions of the css to the css directory and watch the src directory for changes.
It's aliased to the command:

```npm run build:watch```

If you'd like to just build the css once without watching the src directory run

```npm run build```

If you want to check that a class hasn't been redefined or 'mutated' there is a linter to check that all of the classes have only been defined once. This can be useful if you are using another library or have written some of your own css and want to make sure there are no naming collisions. To do this run the command

```npm run mutations```

## Docs
The tachyons docs located at http://tachyons.io are all open source and located at https://github.com/tachyons-css/tachyons-css.github.io

You can clone the docs and use them as a template for documenting your own design system / patterns / components.
While not everything is automated, the component library generation makes it extremely easy to 
generate and organize the documentation for components as demonstrated at http://tachyons.io/components


## Contributing

Please read our [code of conduct](https://github.com/tachyons-css/tachyons/blob/master/code-of-conduct.md) for contributors.

## Websites that Use Tachyons
(if you have a project that uses Tachyons feel free to make a PR to add it to this list)

* https://nicenice.co
* https://coralproject.net
* https://goldenstaterecord.com
* http://www.sogol.co
* https://segment.com
* http://hicuties.com
* https://urlbox.io
* https://community.algolia.com/wordpress/
* http://studiocraft.cc
* http://samueldregan.com
* https://filmstrip.cf
* https://voteplz.com
* http://bluebottlecoffee.com
* http://cyclelove.cc
* http://topher.design
* http://iheanyi.com/
* http://johnotander.com
* https://vimgifs.com
* http://jon.gold/txt
* http://rene.jon.gold
* https://tinychime.github.io/jekyons/
* http://prnt.cc
* http://spenhar.com
* http://randoma11y.com
* http://www.csspurge.com
* http://clrs.cc
* https://cljsjs.github.io
* https://www.getnoodl.es
* https://natwelch.com
* http://pesticide.io
* http://zachhurd.com
* http://gfffs.com
* https://wordpress.org/themes/vanilla-milkshake/
* http://comics.hongkonggong.com/
* https://accessmyinfo.hk/#/
* https://accessmyinfo.org/#/
* http://rene.jon.gold
* http://randoma11y.com
* http://designbytyping.com
* http://colepeters.com
* https://atmin.github.io/funponent/
* http://blog.colepeters.com
* http://aboutlife.com
* http://joinoneroom.com
* http://filipaonunes.com
* https://vakra.band
* http://tylernford.com
* https://adventuretron.org
* https://uptimeumbrella.com
* http://www.talbs.me
* http://seanoshea.me
* https://www.hiaida.com
* http://maxogden.github.io/screencat/
* http://numenta.com
* https://windtoday.co
* http://claudio.netlify.com
* http://devday-ar.com
* http://mrmrs.io/up
* http://mrmrs.io/profile/
* http://mrmrs.io/gradients
* http://mrmrs.io/btns/
* http://mrmrs.io/beats/
* http://mrmrs.io/writing
* http://mrmrs.cc
* http://mn-ml.cc

And of course...
* http://tachyons.io

## Help

If you have a question or need help feel free to open an issue here or jump into the [Tachyons slack channel](http://tachyons-slack-invite.herokuapp.com).

## License

MIT
