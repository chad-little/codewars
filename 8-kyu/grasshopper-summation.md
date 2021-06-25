### [Problem](https://www.codewars.com/kata/55d24f55d7dd296eb9000030/javascript)

Write a program that finds the summation of every number from 1 to num.  
The number will always be a positive integer greater than 0.

#### Example:

```
summation(2) -> 3
1 + 2

summation(8) -> 36
1 + 2 + 3 + 4 + 5 + 6 + 7 + 8
```

```javascript
var summation = function (num) {
  // Code here
};
// Sample Test:
describe("summation", function () {
  it("should return the correct total", function () {
    Test.assertEquals(summation(1), 1);
    Test.assertEquals(summation(8), 36);
  });
});
```

### [Solution](https://www.codewars.com/kata/55d24f55d7dd296eb9000030/solutions/javascript)

```javascript
var summation = function (num) {
  let result = 0;
  for (var i = 1; i <= num; i++) {
    result += i;
  }

  return result;
};
```
