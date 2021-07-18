### [Problem](https://www.codewars.com/kata/55a70521798b14d4750000a4/javascript)

Make a function that will return a greeting statement that uses an input;
your program should return, `"Hello, <name> how are you doing today?"`.

```javascript
function greet(name) {
  //your code here
}
// Sample Test:
const chai = require("chai");
const assert = chai.assert;
chai.config.truncateThreshold = 0;

describe("Basic tests", () => {
  it("Testing for fixed tests", () => {
    assert.strictEqual(greet("Ryan"), "Hello, Ryan how are you doing today?");
    assert.strictEqual(
      greet("Shingles"),
      "Hello, Shingles how are you doing today?"
    );
  });
});
```

### [Solution](https://www.codewars.com/kata/55a70521798b14d4750000a4/solutions/javascript)

```javascript
function greet(name) {
  return `Hello, ${name} how are you doing today?`;
}
```
