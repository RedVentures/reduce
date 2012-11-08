
# reduce

  array reduce

## Installation

  $ component install redventures/reduce

## API

  ```js
  var reduce = require('reduce');

  var numbers = [0, 1, 2, 3, 4, 5];

  var result = reduce(numbers, function(prev, curr){
    return prev + curr;
  });
  ```
   
## License

  Apache, Version 2.0
