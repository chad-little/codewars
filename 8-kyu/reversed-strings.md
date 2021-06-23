### [Problem](https://www.codewars.com/kata/5168bb5dfe9a00b126000018/javascript)

Complete the solution so that it reverses the string passed into it.

```javascript
'world' => 'dlrow'
```

```javascript
function solution(str) {
  // ...
}
// Sample Test:
const { assert } = require("chai");

describe("Basic tests", () => {
  it("Testing for fixed tests", () => {
    assert.strictEqual(solution("world"), "dlrow");
    assert.strictEqual(solution("hello"), "olleh");
    assert.strictEqual(solution(""), "");
    assert.strictEqual(solution("h"), "h");
  });
});
```

### [Solution](https://www.codewars.com/kata/5168bb5dfe9a00b126000018/solutions/javascript)

```javascript
function solution(str) {
  return str.split("").reverse().join("");
}
```
