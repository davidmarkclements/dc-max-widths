# dc-max-widths 1.0.0

Performance based css module.

#### Stats

362 | 48 | 48
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev dc-max-widths
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/dc-max-widths
```

ssh:
```
git clone git@github.com:tachyons-css/dc-max-widths.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "dc-max-widths";
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
<link rel="stylesheet" href="http://npmcdn.com/dc-max-widths@1.0.0/css/dc-max-widths.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/dc-max-widths">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*

   MAX WIDTHS

*/
/* Max Width Percentages */
.mw-100 { max-width: 100%; }
/* Max Width Scale */
.mw1 { max-width: 1rem; }
.mw2 { max-width: 2rem; }
.mw3 { max-width: 4rem; }
.mw4 { max-width: 8rem; }
.mw5 { max-width: 16rem; }
.mw6 { max-width: 32rem; }
.mw7 { max-width: 48rem; }
.mw8 { max-width: 64rem; }
.mw9 { max-width: 96rem; }
.mw10 { max-width: 128rem; }
/* Max Width String Properties */
.mw-none { max-width: none; }
@media screen and (min-width: 30em) {
 .mw-100-ns { max-width: 100%; }
 .mw1-ns { max-width: 1rem; }
 .mw2-ns { max-width: 2rem; }
 .mw3-ns { max-width: 4rem; }
 .mw4-ns { max-width: 8rem; }
 .mw5-ns { max-width: 16rem; }
 .mw6-ns { max-width: 32rem; }
 .mw7-ns { max-width: 48rem; }
 .mw8-ns { max-width: 64rem; }
 .mw9-ns { max-width: 96rem; }
 .mw10-ns { max-width: 128rem; }
 .mw-none-ns { max-width: none; }
}
@media screen and (min-width: 30em) and (max-width: 60em) {
 .mw-100-m { max-width: 100%; }
 .mw1-m { max-width: 1rem; }
 .mw2-m { max-width: 2rem; }
 .mw3-m { max-width: 4rem; }
 .mw4-m { max-width: 8rem; }
 .mw5-m { max-width: 16rem; }
 .mw6-m { max-width: 32rem; }
 .mw7-m { max-width: 48rem; }
 .mw8-m { max-width: 64rem; }
 .mw9-m { max-width: 96rem; }
 .mw10-m { max-width: 128rem; }
 .mw-none-m { max-width: none; }
}
@media screen and (min-width: 60em) {
 .mw-100-l { max-width: 100%; }
 .mw1-l { max-width: 1rem; }
 .mw2-l { max-width: 2rem; }
 .mw3-l { max-width: 4rem; }
 .mw4-l { max-width: 8rem; }
 .mw5-l { max-width: 16rem; }
 .mw6-l { max-width: 32rem; }
 .mw7-l { max-width: 48rem; }
 .mw8-l { max-width: 64rem; }
 .mw9-l { max-width: 96rem; }
 .mw10-l { max-width: 128rem; }
 .mw-none-l { max-width: none; }
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

