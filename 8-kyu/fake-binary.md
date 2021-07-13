### [Problem](https://www.codewars.com/kata/57eae65a4321032ce000002d/javascript)

Given a string of digits, you should replace any digit below 5 with '0' and any  
digit 5 and above with '1'. Return the resulting string.

```javascript
function fakeBin(x) {
  // ...
}
// Sample Test:
const chai = require("chai");
const assert = chai.assert;
chai.config.truncateThreshold = 0;

describe("Basic tests", () => {
  it("Testing for fixed tests", () => {
    assert.strictEqual(fakeBin("45385593107843568"), "01011110001100111");
    assert.strictEqual(fakeBin("509321967506747"), "101000111101101");
    assert.strictEqual(
      fakeBin("366058562030849490134388085"),
      "011011110000101010000011011"
    );
  });
});
```

### [Solution](https://www.codewars.com/kata/57eae65a4321032ce000002d/solutions/javascript)

```javascript
function fakeBin(x) {
  return x
    .split("")
    .map((n) => (n < 5 ? 0 : 1))
    .join("");
}
```
