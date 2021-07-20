### [Problem](https://www.codewars.com/kata/57cc975ed542d3148f00015b/javascript)

You will be given an array `a` and a value `x`. All you need to do is check  
whether the provided array contains the value.

Array can contain numbers or strings. X can be either.

Return `true` if the array contains the value, `false` if not.

```javascript
function check(a, x) {
  // your code here
}
// Sample Test:
const chai = require("chai");
const assert = chai.assert;
chai.config.truncateThreshold = 0;

describe("Basic tests", () => {
  it("Testing for fixed tests", () => {
    assert.strictEqual(check([66, 101], 66), true);
    assert.strictEqual(check([101, 45, 75, 105, 99, 107], 107), true);
    assert.strictEqual(check(["t", "e", "s", "t"], "e"), true);
    assert.strictEqual(check(["what", "a", "great", "kata"], "kat"), false);
  });
});
```

### [Solution](https://www.codewars.com/kata/57cc975ed542d3148f00015b/solutions/javascript)

```javascript
function check(a, x) {
  return a.includes(x);
}
```
