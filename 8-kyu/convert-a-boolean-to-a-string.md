### [Problem](https://www.codewars.com/kata/551b4501ac0447318f0009cd/javascript)

Implement a function which convert the given boolean value into its string  
representation.

Note: Only valid inputs will be given.

```javascript
function booleanToString(b) {
  //your code here
}
// Sample Test:
describe("Tests", () => {
  it("test", () => {
    Test.assertEquals(
      booleanToString(true),
      "true",
      'When we pass in true, we want the string "true" as output'
    );
    Test.assertEquals(
      booleanToString(false),
      "false",
      'When we pass in false, we want the string "false" as output'
    );
  });
});
```

### [Solution](https://www.codewars.com/kata/551b4501ac0447318f0009cd/solutions/javascript)

```javascript
function booleanToString(b) {
  return b.toString();
}
```
