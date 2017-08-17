# noVNC-node

Fork of [noVNC](https://github.com/kanaka/noVNC) to be used with Node/browserify.


## Installation

* With **npm**:

```bash
$ npm install --save novnc-module
```


## Usage in Node/browserify

```javascript
var noVNC = require('novnc-module');
```



## Documentation

Read the full [API documentation](docs/index.md) in the *docs* folder.


## Development

[Node.js](http://nodejs.org) must be installed.

Install `gulp-cli` 4.0 globally (which provides the `gulp` command):

```bash
$ npm install -g gulpjs/gulp-cli#4.0
```

(you can also use the local `gulp` executable located in `node_modules/.bin/gulp`).

Get the source code:

```bash
$ git clone https://github.com/bruteforce/noVNC.git
$ cd noVNC/
```

Install dependencies:

```bash
$ npm install
```

And run `gulp` (or `node_modules/.bin/gulp`):

```bash
$ gulp
```
