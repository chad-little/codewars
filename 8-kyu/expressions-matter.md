### [Problem](https://www.codewars.com/kata/5ae62fcf252e66d44d00008e/javascript)

Given three integers `a` ,`b` ,`c`, return the largest number obtained after inserting  
the following operators and brackets: `+`, `_`, `()`

In other words , <em>try every combination of a,b,c with [_+()] , and return the  
Maximum Obtained</em>

#### Example:

<em>With the numbers are 1, 2 and 3 , here are some ways of placing signs and brackets:</em>

```
1 * (2 + 3) = 5
1 * 2 * 3 = 6
1 + 2 _ 3 = 7
(1 + 2) _ 3 = 9
```

So the maximum value that you can obtain is 9.

```javascript
function expressionMatter(a, b, c) {
 return // highest achievable result
}
// Sample Test:
const chai = require("chai");
const assert = chai.assert;
chai.config.truncateThreshold=0;

describe("Fixed tests", function() {
 it("Small values", function() {
   assert.strictEqual(expressionMatter(2, 1, 2), 6);
   assert.strictEqual(expressionMatter(2, 1, 1), 4);
   assert.strictEqual(expressionMatter(1, 1, 1), 3);
   assert.strictEqual(expressionMatter(1, 2, 3), 9);
   assert.strictEqual(expressionMatter(1, 3, 1), 5);
   assert.strictEqual(expressionMatter(2, 2, 2), 8);
 });
```

### [Solution](https://www.codewars.com/kata/5ae62fcf252e66d44d00008e/solutions/javascript)

```javascript
function expressionMatter(a, b, c) {
  return Math.max(a + b + c, a * b * c, (a + b) * c, a * (b + c));
}
```
