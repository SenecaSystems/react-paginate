# react-paginate

**A ReactJS component to render a pagination.**

By installing this component and writing only a little bit of CSS you can obtain this:

<img src="./docs/img/pagination2.png" alt="Pagination sample 2" />

or

<img src="./docs/img/pagination1.png" alt="Pagination sample 1" />

## Installation

Install `react-paginate` with [npm](https://www.npmjs.com/):

```
$ npm install react-paginate
```

For [CommonJS](http://wiki.commonjs.org/wiki/CommonJS) users:

```javascript
var ReactPaginate = require('react-paginate');
```

Read the code of [sample/sample.jsx][1]. You will quickly understand
how to make `react-paginate` work with a list of objects.

## Sample project (demo)

Clone the repository and move into:

```console
$ git clone git@github.com:AdeleD/react-paginate.git
$ cd react-paginate
```

Install dependencies:

```console
$ make install
```

Prepare the demo:

```console
$ make sample
```

Run the server:

```console
$ make serve
```

Open your browser and go to `http://localhost:3000/`.

## Contribute

1. [Submit an issue](https://github.com/AdeleD/react-paginate/issues)
2. Fork the repository
3. Create a dedicated branch (never ever work in `master`)
4. Fix bugs or implement features
5. Always write tests

Run tests:

```console
$ make test
```

[1]: https://github.com/AdeleD/react-paginate/blob/master/sample/sample.jsx
