*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/to-slug-case](http://github.com/ianstormtaylor/to-slug-case). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-to-slug-case`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# to-slug-case

  Convert a string to a slug case.

## Installation

    $ component install ianstormtaylor/to-slug-case
    $ npm install to-slug-case

## Example

```js
var slug = require('to-slug-case');

slug('camelCase');  // "camel-case"
slug('space case'); // "snake-case"
slug('dot.case');   // "dot-case"
slug('weird[case'); // "weird-case"
```

## API

### toSlugCase(string)
  
  Returns the slug-case variant of a `string`.

## License

  MIT
