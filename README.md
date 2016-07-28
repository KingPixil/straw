# Straw

flexible templating for node.js

## Usage

Install it:

```sh
$ npm install strawjs
```

Use it

```js
var straw = require('strawjs');

var html = straw.parse('index.html', {
    myVar: 'Hello World';
});

// this parses index.html and replaces
// {{myVar}}
// with 'Hello World'
// and returns the new html, you can now send it
```