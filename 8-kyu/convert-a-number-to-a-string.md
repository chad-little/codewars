### [Problem](https://www.codewars.com/kata/5265326f5fda8eb1160004c8/javascript)

We need a function that can transform a number into a string.

What ways of achieving this do you know?

#### Examples:

```
123 --> "123"
999 --> "999"
```

```javascript
function numberToString(num) {
  // Return a string of the number here!
}
// Sample Test:
describe("Tests", () => {
  it("test", () => {
    Test.assertEquals(numberToString(67), "67");
  });
});
```

### [Solution](https://www.codewars.com/kata/5265326f5fda8eb1160004c8/solutions/javascript)

```javascript
function numberToString(num) {
  return num.toString();
}
```
