<!-- [![Express Logo](https://i.cloudup.com/zfY6lL7eFa-3000x3000.png)](http://expressjs.com/) -->

# Express

  Fast, unopinionated, minimalist web framework for [node](http://nodejs.org).

  [![NPM Version][npm-image]][npm-url]
  [![NPM Downloads][downloads-image]][downloads-url]
  [![Node.js Version][node-version-image]][node-version-url]
  [![Build Status][travis-image]][travis-url]
  [![Test Coverage][coveralls-image]][coveralls-url]
  [![GitTip][gittip-image]][gittip-url]

```js
var express = require('express')
var app = express()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)
```

  **PROTIP** Be sure to read [Migrating from 3.x to 4.x](https://github.com/strongloop/express/wiki/Migrating-from-3.x-to-4.x) as well as [New features in 4.x](https://github.com/strongloop/express/wiki/New-features-in-4.x).

### Installation

```bash
$ npm install express
```

## Quick Start

  The quickest way to get started with express is to utilize the executable [`express(1)`](https://github.com/expressjs/generator) to generate an application as shown below:

  Install the executable. The executable's major version will match Express's:

```bash
$ npm install -g express-generator@4
```

  Create the app:

```bash
$ express /tmp/foo && cd /tmp/foo
```

  Install dependencies:

```bash
$ npm install
```

  Start the server:

```bash
$ npm start
```

## Features

  * Robust routing
  * HTTP helpers (redirection, caching, etc)
  * View system supporting 14+ template engines
  * Content negotiation
  * Focus on high performance
  * Executable for generating applications quickly
  * High test coverage

## Philosophy

  The Express philosophy is to provide small, robust tooling for HTTP servers, making
  it a great solution for single page applications, web sites, hybrids, or public
  HTTP APIs.

  Express does not force you to use any specific ORM or template engine. With support for over
  14 template engines via [Consolidate.js](https://github.com/visionmedia/consolidate.js),
  you can quickly craft your perfect framework.

## More Information

  * [Website and Documentation](http://expressjs.com/) - [[website repo](https://github.com/strongloop/expressjs.com)]
  * [Github Organization](https://github.com/expressjs) for Official Middleware & Modules
  * [#express](https://webchat.freenode.net/?channels=express) on freenode IRC
  * Visit the [Wiki](https://github.com/strongloop/express/wiki)
  * [Google Group](https://groups.google.com/group/express-js) for discussion
  * [Русскоязычная документация](http://jsman.ru/express/)
  * [한국어 문서](http://expressjs.kr) - [[website repo](https://github.com/Hanul/expressjs.kr)]
  * Run express examples [online](https://runnable.com/express)

## Examples

  To view the examples, clone the Express repo & install the dependancies:

```bash
$ git clone git://github.com/strongloop/express.git --depth 1
$ cd express
$ npm install
```

  Then run whichever example you want:

```bash
$ node examples/content-negotiation
```

## Tests

  To run the test suite, first install the dependancies, then run `npm test`:

```bash
$ npm install
$ npm test
```

### Contributors

 * Author: [TJ Holowaychuk](https://github.com/visionmedia)
 * Lead Maintainer: [Douglas Christopher Wilson](https://github.com/dougwilson)
 * [All Contributors](https://github.com/strongloop/express/graphs/contributors)

### [MIT Licensed](LICENSE)

[npm-image]: https://img.shields.io/npm/v/express.svg?style=flat
[npm-url]: https://npmjs.org/package/express
[node-version-image]: https://img.shields.io/node/v/express.svg?style=flat
[node-version-url]: http://nodejs.org/download/
[travis-image]: https://img.shields.io/travis/strongloop/express.svg?style=flat
[travis-url]: https://travis-ci.org/strongloop/express
[coveralls-image]: https://img.shields.io/coveralls/strongloop/express.svg?style=flat
[coveralls-url]: https://coveralls.io/r/strongloop/express?branch=master
[downloads-image]: https://img.shields.io/npm/dm/express.svg?style=flat
[downloads-url]: https://npmjs.org/package/express
[gittip-image]: https://img.shields.io/gittip/dougwilson.svg?style=flat
[gittip-url]: https://www.gittip.com/dougwilson/
