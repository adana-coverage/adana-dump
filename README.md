# adana-dump

Output [adana] coverage information after node process ends.

![build status](http://img.shields.io/travis/adana-coverage/adana-dump/master.svg?style=flat)
![coverage](http://img.shields.io/coveralls/adana-coverage/adana-dump/master.svg?style=flat)
![license](http://img.shields.io/npm/l/adana-dump.svg?style=flat)
![version](http://img.shields.io/npm/v/adana-dump.svg?style=flat)
![downloads](http://img.shields.io/npm/dm/adana-dump.svg?style=flat)

Load this library into your node program to have the resulting coverage data output to a file after.

## Usage

You can see the examples in the [adana] repository for real world usage with testing frameworks like [mocha].

Install the software:

```sh
npm install --save-dev adana-dump
```

Setup your `.babelrc` to use it:

```javascript
require('adana-dump'); // coverage will now be output
```

[adana]: https://github.com/adana-coverage/babel-plugin-transform-adana
[mocha]: http://mochajs.org/
