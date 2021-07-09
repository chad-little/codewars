### [Problem](https://www.codewars.com/kata/5899dc03bc95b1bf1b0000ad/javascript)

Given a set of numbers, return the additive inverse of each. Each positive  
becomes negatives, and the negatives become positives.

#### Example:

```
invert([1,2,3,4,5]) == [-1,-2,-3,-4,-5]
invert([1,-2,3,-4,5]) == [-1,2,-3,4,-5]
invert([]) == []
```

You can assume that all values are integers. Do not mutate the input array/list.

```javascript
function invert(array) {
  return;
}
// Sample Test:
const chai = require("chai");
const assert = chai.assert;
chai.config.truncateThreshold = 0;

describe("Invert array values", () => {
  it("Basic Tests", () => {
    assert.deepEqual(invert([1, 2, 3, 4, 5]), [-1, -2, -3, -4, -5]);
    assert.deepEqual(invert([1, -2, 3, -4, 5]), [-1, 2, -3, 4, -5]);
    assert.deepEqual(invert([]), []);
    assert.deepEqual(invert([0]), [-0]);
  });
});
```

### [Solution](https://www.codewars.com/kata/5899dc03bc95b1bf1b0000ad/solutions/javascript)

```javascript
function invert(array) {
  return array.map((i) => -i);
}
```
