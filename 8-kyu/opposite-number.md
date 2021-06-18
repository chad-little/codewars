### [Problem](https://www.codewars.com/kata/56dec885c54a926dcd001095/javascript)

Very simple, given a number, find its opposite.

#### Examples:

```
1: -1
14: -14
-34: 34
```

```javascript
function opposite(number) {
  //your code here
}
// Sample Test:
describe("Tests", () => {
  it("test", () => {
    Test.assertEquals(opposite(1), -1);
  });
});
```

### [Solution](https://www.codewars.com/kata/56dec885c54a926dcd001095/solutions/javascript)

```javascript
function opposite(number) {
  return -number;
}
```
