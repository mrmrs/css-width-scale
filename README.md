# css-width-scale 0.0.6

Css module of single purpose classes for width scale

#### Stats

286 | 40 | 40
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-width-scale
```

#### With Git

```
git clone https://github.com/tachyons-css/css-width-scale
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-width-scale";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-width-scale">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   WIDTHS
*/
/* Width Percentages */
.wi1 { width: 1rem; }
.wi2 { width: 2rem; }
.wi3 { width: 4rem; }
.wi4 { width: 8rem; }
.wi5 { width: 16rem; }
.wi6 { width: 32rem; }
.wi7 { width: 48rem; }
.wi8 { width: 64rem; }
.wi9 { width: 96rem; }
.wi10 { width: 128rem; }
@media screen and (min-width: 48em) {
 .wi1-ns { width: 1rem; }
 .wi2-ns { width: 2rem; }
 .wi3-ns { width: 4rem; }
 .wi4-ns { width: 8rem; }
 .wi5-ns { width: 16rem; }
 .wi6-ns { width: 32rem; }
 .wi7-ns { width: 48rem; }
 .wi8-ns { width: 64rem; }
 .wi9-ns { width: 96rem; }
 .wi10-ns { width: 128rem; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .wi1-m { width: 1rem; }
 .wi2-m { width: 2rem; }
 .wi3-m { width: 4rem; }
 .wi4-m { width: 8rem; }
 .wi5-m { width: 16rem; }
 .wi6-m { width: 32rem; }
 .wi7-m { width: 48rem; }
 .wi8-m { width: 64rem; }
 .wi9-m { width: 96rem; }
 .wi10-m { width: 128rem; }
}
@media screen and (min-width: 64em) {
 .wi1-l { width: 1rem; }
 .wi2-l { width: 2rem; }
 .wi3-l { width: 4rem; }
 .wi4-l { width: 8rem; }
 .wi5-l { width: 16rem; }
 .wi6-l { width: 32rem; }
 .wi7-l { width: 48rem; }
 .wi8-l { width: 64rem; }
 .wi9-l { width: 96rem; }
 .wi10-l { width: 128rem; }
}
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

MIT

