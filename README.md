# JavaScript Templates

## Contents

- [Demo](https://blueimp.github.io/JavaScript-Templates/)
- [Description](#description)
- [Usage](#usage)
  - [Client-side](#client-side)
  - [Server-side](#server-side)
- [Requirements](#requirements)
- [API](#api)
  - [tmpl() function](#tmpl-function)
  - [Templates cache](#templates-cache)
  - [Output encoding](#output-encoding)
  - [Local helper variables](#local-helper-variables)
  - [Template function argument](#template-function-argument)
  - [Template parsing](#template-parsing)
- [Templates syntax](#templates-syntax)
  - [Interpolation](#interpolation)
  - [Evaluation](#evaluation)
- [Compiled templates](#compiled-templates)
- [Tests](#tests)
- [License](#license)

## Description

1KB lightweight, fast & powerful JavaScript templating engine with zero
dependencies.  
Compatible with server-side environments like [Node.js](https://nodejs.org/),
module loaders like [RequireJS](https://requirejs.org/) or
[webpack](https://webpack.js.org/) and all web browsers.

## Usage

### Client-side

Include the (minified) JavaScript Templates script in your HTML markup:

```html
<script src="js/tmpl.min.js"></script>
```
## Tests

The JavaScript Templates project comes with
[Unit Tests](https://en.wikipedia.org/wiki/Unit_testing).  
There are two different ways to run the tests:

- Open test/index.html in your browser or
- run `npm test` in the Terminal in the root path of the repository package.

The first one tests the browser integration, the second one the
[Node.js](https://nodejs.org/) integration.

## License

The JavaScript Templates script is released under the
[MIT license](https://opensource.org/licenses/MIT).
