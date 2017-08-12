# codename-titans

> Greek titan names parser for [Codename](https://github.com/khaosdoctor/Codename) (Standalone)

## Usage

Install the package using either `npm install codename-titans --save` or `yarn add codename-titans`.

Require it and use the function `parse`:

```js
const titan = require('codename-titans')

console.log(titan.parse('2.1.4').codenameText) // V2.1.4 - Tethys
```

For more information about the API, see [Codename](https://github.com/khaosdoctor/Codename) project, this parser only abstracts the `parse` function, returning an instance of the original Codename parser