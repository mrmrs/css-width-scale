# css-width-scale 1.0.3

Css module of single purpose classes for width scale

#### Stats

290 | 40 | 40
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-width-scale
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-width-scale
```

ssh:
```
git clone git@github.com:tachyons-css/css-width-scale.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-width-scale";
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
<link rel="stylesheet" href="http://unpkg.com/css-width-scale@1.0.2/css/css-width-scale.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-width-scale">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/* Media Queries */
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
@media (min-width: 48em) {
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
@media (min-width: 48em) and (max-width: 64em) {
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
@media  (min-width: 64em) {
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

ISC

