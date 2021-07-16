### [Problem](https://www.codewars.com/kata/57a2013acf1fa5bfc4000921/javascript)

Write a function which calculates the average of the numbers in a given list.

Note: Empty arrays should return 0.

```javascript
function find_average(array) {
  // your code here
  return 0;
}
// Sample Test:
const chai = require("chai");
const assert = chai.assert;
chai.config.truncateThreshold = 0;

describe("Basic tests", () => {
  it("Testing for fixed tests", () => {
    assert.strictEqual(find_average([1, 1, 1]), 1);
    assert.strictEqual(find_average([1, 2, 3]), 2);
    assert.strictEqual(find_average([1, 2, 3, 4]), 2.5);
  });
});
```

### [Solution](https://www.codewars.com/kata/57a2013acf1fa5bfc4000921/solutions/javascript)

```javascript
function find_average(array) {
  const sum = array.reduce((a, b) => a + b, 0);
  const avg = sum / array.length || 0;
  return avg;
}
```
