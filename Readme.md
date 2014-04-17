*This repository is a mirror of the [component](http://component.io) module [ripplejs/array-observer](http://github.com/ripplejs/array-observer). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ripplejs-array-observer`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# array-observer

[![Build Status](https://travis-ci.org/ripplejs/array-observer.png?branch=master)](https://travis-ci.org/ripplejs/array-observer)

  Watch an array for changes

## Installation

  Install with [component(1)](http://component.io):

    $ component install ripplejs/array-observer

## API

```js
var observe = require('array-observer');
var items = [];

observer = observe(items);

observer.on('add', function(val){
  console.log(val);
});

items.push("Hello"); // Hello
```

## License

  The MIT License (MIT)

  Copyright (c) 2014 <copyright holders>

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