## Lodash Curry

- Creates a function that accepts arguments of func and either invokes func returning its result

var abc = function(a, b, c) {
  return [a, b, c];
};
 
- the top function does the same thing as the curry function on the bottom

var curried = _.curry(abc);
 
curried(1)(2)(3);
// => [1, 2, 3]

