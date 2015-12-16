
# reduce

  array reduce

## Installation

```sh
  $ component install redventures/reduce
```

## API

```js
var reduce = require('reduce');

var numbers = [0, 1, 2, 3, 4, 5];

var result = reduce(numbers, function(prev, curr){
  return prev + curr;
});
```
   
## License
Copyright 2012-2015 Red Ventures

reduce is dual licensed under the MIT and Apache version 2.0 licenses.  

See LICENSE for additional information.


