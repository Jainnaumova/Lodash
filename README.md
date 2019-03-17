# Lodash

```javascript
_.chunk(['a', 'b', 'c', 'd', 'e', 'f', 'g'], 3)
// => [ [ 'a', 'b', 'c' ], [ 'd', 'e', 'f' ], [ 'g' ] ]

_.difference([2, 1, 3, 4], [2, 4])
// => [1, 3]

_.last([1, 2, 3, 4])
// => 4

_.intersection([4, 5, 6 ], [3, 5, 6])
// => [5, 6]

_.uniq([2, 1, 2, 3])
// => [2, 1, 3]

_.zipObject(['a', 'b', 'c'], [1, 2, 3])
// => { 'a': 1, 'b': 2, c: 3 }

const students = [
  {‘student’: 'alice', 'age': 12, 'active': true },
  {‘student’: 'max', 'age': 13, 'active': false}
];
_.filter(students, function(o) { return !o.active; });                                                         // => [ { student: 'max', age: 13, active: false } ]

_.shuffle([1, 2, 3, 4])
// => [4, 1, 3, 2]

const object = { 'a': 1, 'b': '2', 'c': 3 };
_.pick(object, ['a', 'b']);
// => { a: 1, b: '2' }

const students = {
  'alice': { 'student': 'alice', 'age': 12 },
  'max': { 'student': 'max', 'age': 13 }
};
_.mapValues(students, function(y) { return y.age; })
// => { alice: 12, max: 13 }
```
