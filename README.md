# css-image-orientation 1.0.6

Css module of single purpose classes for image orientation

#### Stats

297 | 32 | 32
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-image-orientation
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-image-orientation
```

ssh:
```
git clone git@github.com:tachyons-css/css-image-orientation.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-image-orientation";
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
<link rel="stylesheet" href="http://unpkg.com/css-image-orientation@1.0.6/css/css-image-orientation.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-image-orientation">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   IMAGE ORIENTATION
*/
.img-turn-45 { image-orientation: 45deg; }
.img-turn-90 { image-orientation: 90deg; }
.img-turn-135 { image-orientation: 135deg; }
.img-turn-180 { image-orientation: 180deg; }
.img-turn-225 { image-orientation: 225deg; }
.img-turn-270 { image-orientation: 270deg; }
.img-turn-315 { image-orientation: 315deg; }
.img-turn-360 { image-orientation: 360deg; }
@media screen and (min-width: 48em) {
 .img-turn-45-ns { image-orientation: 45deg; }
 .img-turn-90-ns { image-orientation: 90deg; }
 .img-turn-135-ns { image-orientation: 135deg; }
 .img-turn-180-ns { image-orientation: 180deg; }
 .img-turn-225-ns { image-orientation: 225deg; }
 .img-turn-270-ns { image-orientation: 270deg; }
 .img-turn-315-ns { image-orientation: 315deg; }
 .img-turn-360-ns { image-orientation: 360deg; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .img-turn-45-m { image-orientation: 45deg; }
 .img-turn-90-m { image-orientation: 90deg; }
 .img-turn-135-m { image-orientation: 135deg; }
 .img-turn-180-m { image-orientation: 180deg; }
 .img-turn-225-m { image-orientation: 225deg; }
 .img-turn-270-m { image-orientation: 270deg; }
 .img-turn-315-m { image-orientation: 315deg; }
 .img-turn-360-m { image-orientation: 360deg; }
}
@media screen and (min-width: 64em) {
 .img-turn-45-l { image-orientation: 45deg; }
 .img-turn-90-l { image-orientation: 90deg; }
 .img-turn-135-l { image-orientation: 135deg; }
 .img-turn-180-l { image-orientation: 180deg; }
 .img-turn-225-l { image-orientation: 225deg; }
 .img-turn-270-l { image-orientation: 270deg; }
 .img-turn-315-l { image-orientation: 315deg; }
 .img-turn-360-l { image-orientation: 360deg; }
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

