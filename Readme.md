*This repository is a mirror of the [component](http://component.io) module [component/querystring](http://github.com/component/querystring). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-querystring`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# querystring

  Simple key / value pair query-string parser and formatter.

## Installation

```
$ component install component/querystring
```

## API

### .parse(string)

  Parse the given query `string`:

```js
var query = require('querystring');
query.parse('name=tobi&species=ferret');
// => { name: 'tobi', species: 'ferret' }
```

### .stringify(object)

  Stringify the given `object`:

```js
var query = require('querystring');
query.stringify({ name: 'tobi', species: 'ferret' });
// => "name=tobi&species=ferret"
```

## License

  MIT
