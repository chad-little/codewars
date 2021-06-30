### [Problem](https://www.codewars.com/kata/515e271a311df0350d00000f/javascript)

Complete the square sum function so that it squares each number passed into it  
and then sums the results together.

For example, for `[1, 2, 2]` it should return `9` because `1^2 + 2^2 + 2^2 = 9`.

```javascript
function squareSum(numbers) {
  // ...
}
// Sample Test:
describe("Tests", () => {
  it("test", () => {
    Test.assertEquals(squareSum([1, 2]), 5);
    Test.assertEquals(squareSum([0, 3, 4, 5]), 50);
  });
});
```

### [Solution](https://www.codewars.com/kata/515e271a311df0350d00000f/solutions/javascript)

```javascript
function squareSum(numbers) {
  let total = 0;
  for (i = 0; i < numbers.length; i++) {
    total += numbers[i] ** 2;
  }
  return total;
}
```
