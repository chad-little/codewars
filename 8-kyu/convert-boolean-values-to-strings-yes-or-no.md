### [Problem](https://www.codewars.com/kata/53369039d7ab3ac506000467/javascript)

Complete the method that takes a boolean value and return a `"Yes"` string for  
`true`, or a `"No"` string for `false`.

```javascript
function boolToWord(bool) {
  //...
}
// Sample Test:
const { assert } = require("chai");

describe("Basic tests", () => {
  it("Testing for basic tests", () => {
    assert.strictEqual(boolToWord(true), "Yes");
    assert.strictEqual(boolToWord(false), "No");
  });
});
```

### [Solution](https://www.codewars.com/kata/53369039d7ab3ac506000467/solutions/javascript)

```javascript
function boolToWord(bool) {
  return bool ? "Yes" : "No";
}
```
