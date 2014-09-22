# CSS IMAGE ORIENTATION

  Mobile-first classes for css-image-orientation.
  Set the desired css-image-orientation on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-image-orientation
```
View on [npm](https://www.npmjs.org/package/css-image-orientation)


## File Size

1.7K image-orientation.css
1.4K image-orientation.min.css

## The Code
```
  .img-turn-45  { image-orientation: 45deg;  }
  .img-turn-90  { image-orientation: 90deg;  }
  .img-turn-135 { image-orientation: 135deg; }
  .img-turn-180 { image-orientation: 180deg; }
  .img-turn-225 { image-orientation: 225deg; }
  .img-turn-270 { image-orientation: 270deg; }
  .img-turn-315 { image-orientation: 315deg; }
  .img-turn-360 { image-orientation: 360deg; }

@media screen and (min-width: 48em) {
  .img-turn-45-ns  { image-orientation: 45deg;  }
  .img-turn-90-ns  { image-orientation: 90deg;  }
  .img-turn-135-ns { image-orientation: 135deg; }
  .img-turn-180-ns { image-orientation: 180deg; }
  .img-turn-225-ns { image-orientation: 225deg; }
  .img-turn-270-ns { image-orientation: 270deg; }
  .img-turn-315-ns { image-orientation: 315deg; }
  .img-turn-360-ns { image-orientation: 360deg; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .img-turn-45-m  { image-orientation: 45deg;  }
  .img-turn-90-m  { image-orientation: 90deg;  }
  .img-turn-135-m { image-orientation: 135deg; }
  .img-turn-180-m { image-orientation: 180deg; }
  .img-turn-225-m { image-orientation: 225deg; }
  .img-turn-270-m { image-orientation: 270deg; }
  .img-turn-315-m { image-orientation: 315deg; }
  .img-turn-360-m { image-orientation: 360deg; }
}

@media screen and (min-width: 64em)  {
  .img-turn-45-l  { image-orientation: 45deg;  }
  .img-turn-90-l  { image-orientation: 90deg;  }
  .img-turn-135-l { image-orientation: 135deg; }
  .img-turn-180-l { image-orientation: 180deg; }
  .img-turn-225-l { image-orientation: 225deg; }
  .img-turn-270-l { image-orientation: 270deg; }
  .img-turn-315-l { image-orientation: 315deg; }
  .img-turn-360-l { image-orientation: 360deg; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

