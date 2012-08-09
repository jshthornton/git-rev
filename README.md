# git-rev

[![Build Status](https://secure.travis-ci.org/tblobaum/git-rev.png)](http://travis-ci.org/tblobaum/git-rev)

# Example

``` js
var revision = require('git-rev')

revision.short(function (str) {
  console.log('revision short', str)
})

revision.long(function (str) {
  console.log('revision long', str)
})

revision.branch(function (str) {
  console.log('revision branch', str)
})

revision.tag(function (str) {
  console.log('revision tag', str)
})

```

# Install

`npm install git-rev`

# License

(The MIT License)

Copyright (c) 2012 Thomas Blobaum <tblobaum@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.