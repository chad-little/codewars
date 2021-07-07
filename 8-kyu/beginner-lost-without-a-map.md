### [Problem](https://www.codewars.com/kata/57f781872e3d8ca2a000007e/javascript)

Given an array of integers, return a new array with each value doubled.

#### For example:

`[1, 2, 3] --> [2, 4, 6]`

For the beginner, try to use the `map` method - it comes in very handy quite  
a lot so is a good one to know.

```javascript
function maps(x) {
  //...
}
// Sample Test:
describe("Example tests", () => {
  Test.assertDeepEquals(maps([1, 2, 3]), [2, 4, 6]);
  Test.assertDeepEquals(maps([4, 1, 1, 1, 4]), [8, 2, 2, 2, 8]);
  Test.assertDeepEquals(maps([2, 2, 2, 2, 2, 2]), [4, 4, 4, 4, 4, 4]);
});
```

### [Solution](https://www.codewars.com/kata/57f781872e3d8ca2a000007e/solutions/javascript)

```javascript
function maps(x) {
  return x.map((n) => n * 2);
}
```
