<img src="https://img.shields.io/codecov/c/github/rizafahmi/nama-gadungan" />
<img src="https://img.shields.io/github/repo-size/rizafahmi/nama-gadungan" />

# nama-gadungan

A small library that can help you to get random names for fake data or _dummy_ data that can be used for applications and databases. This library is intended for experimentation for those who wish to learn to contribute to opensource projects. See the manufacturing process on [youtube](https://www.youtube.com/playlist?list=PLTY2nW4jwtG_5wjvX1hFqgRe_QbcLVsWS).


## Installation

### Use NPM

```
npm install nama-gadungan
```

### Use CDN

```
<script src="https://unpkg.com/nama-gadungan@1.0.0/dist/bundle.js" type="module"></script>
```

## How to use

### Node.js
```javascript
const { random } = require('nama-gadungan');

const name = random();
console.log(name);
```

### Browser

```html
<!doctype html -->
<html>
  <head>
    <title>Nama Gadungan Example Usage</title>
  </head>
  <body>

    <script src="https://unpkg.com/nama-gadungan@1.0.0/dist/bundle.js" type="module"></script>
    <script type="module">
      import { random } from './bundle.js';

      console.log(random());
    </script>
  </body>
</html>
```

## How to contribute

* Fork this repository
* Clone this repository
* Make change or improvements
* Make a test case
* Push and Pull Request

## TODO
- [x] Change license in package.json
- [ ] Complete README
- [x] Add file LICENSE
- [x] Indonesian and English Language
