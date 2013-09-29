
# async-map

asynchronous map

## Installation

```sh
$ component install stagas/async-map
```

## Usage

#### map(array, fn, callback)

## Example

```js
var map = require('async-map');

map([1, 2, 3], function(el, fn){
  fn(null, el + 1);
}, function(err, res){
  console.log(res); // [2, 3, 4]
});
```

## License

MIT
