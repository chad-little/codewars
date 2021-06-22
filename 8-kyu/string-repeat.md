### [Problem](https://www.codewars.com/kata/57a0e5c372292dd76d000d7e/javascript)

Write a function called `repeatStr` which repeats the given string `string`  
exactly `n` times.

```javascript
repeatStr(6, "I"); // "IIIIII"
repeatStr(5, "Hello"); // "HelloHelloHelloHelloHello"
```

```javascript
function repeatStr(n, s) {
  return "";
}
// Sample Test:
describe("Tests", function () {
  it("Basic tests", function () {
    Test.assertSimilar(repeatStr(3, "*"), "***");
    Test.assertSimilar(repeatStr(5, "#"), "#####");
    Test.assertSimilar(repeatStr(2, "ha "), "ha ha ");
  });
});
```

### [Solution](https://www.codewars.com/kata/57a0e5c372292dd76d000d7e/solutions/javascript)

```javascript
function repeatStr(n, s) {
  return s.repeat(n);
}
```
