# CSS WIDTH SCALE

  Mobile-first classes for css-width-scale.
  Set the desired css-width-scale on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-width-scale
```
or download the css on github and include in your project.

## File Size


## The Code
```
.wi1 {  width: 1rem; }
.wi2 {  width: 2rem; }
.wi3 {  width: 4rem; }
.wi4 {  width: 8rem; }
.wi5 {  width: 16rem; }
.wi6 {  width: 32rem; }
.wi7 {  width: 48rem; }
.wi8 {  width: 64rem; }
.wi9 {  width: 96rem; }
.wi10 { width: 128rem; }

@media screen and (min-width: 48em) {
  .wi1-ns {  width: 1rem; }
  .wi2-ns {  width: 2rem; }
  .wi3-ns {  width: 4rem; }
  .wi4-ns {  width: 8rem; }
  .wi5-ns {  width: 16rem; }
  .wi6-ns {  width: 32rem; }
  .wi7-ns {  width: 48rem; }
  .wi8-ns {  width: 64rem; }
  .wi9-ns {  width: 96rem; }
  .wi10-ns { width: 128rem; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .wi1-m {      width: 1rem; }
  .wi2-m {      width: 2rem; }
  .wi3-m {      width: 4rem; }
  .wi4-m {      width: 8rem; }
  .wi5-m {      width: 16rem; }
  .wi6-m {      width: 32rem; }
  .wi7-m {      width: 48rem; }
  .wi8-m {      width: 64rem; }
  .wi9-m {      width: 96rem; }
  .wi10-m {     width: 128rem; }
}

@media screen and (min-width: 64em)  {
  .wi1-l {      width: 1rem; }
  .wi2-l {      width: 2rem; }
  .wi3-l {      width: 4rem; }
  .wi4-l {      width: 8rem; }
  .wi5-l {      width: 16rem; }
  .wi6-l {      width: 32rem; }
  .wi7-l {      width: 48rem; }
  .wi8-l {      width: 64rem; }
  .wi9-l {      width: 96rem; }
  .wi10-l {     width: 128rem; }
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

