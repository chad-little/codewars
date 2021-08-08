### [Problem](https://www.codewars.com/kata/57a0556c7cb1f31ab3000ad7/javascript)

Write a function which converts the input string to uppercase.

```javascript
function makeUpperCase(str) {
  // Code here
}
// Sample Test:
describe("Basic Tests", function () {
  it("should pass the basic tests", function () {
    Test.assertEquals(makeUpperCase("hello"), "HELLO");
  });
});
```

### [Solution](https://www.codewars.com/kata/57a0556c7cb1f31ab3000ad7/solutions/javascript)

```javascript
function makeUpperCase(str) {
  return str.toUpperCase();
}
```
