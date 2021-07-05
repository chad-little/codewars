### [Problem](https://www.codewars.com/kata/5583090cbe83f4fd8c000051/javascript)

Given a random non-negative number, you have to return the digits of this  
number within an array in reverse order.

#### Example:

`348597 => [7,9,5,8,4,3]`

```javascript
function digitize(n) {
  //code here
}
// Sample Test:
describe("Tests", () => {
  it("test", () => {
    Test.assertDeepEquals(digitize(35231), [1, 3, 2, 5, 3]);
  });
});
```

### [Solution](https://www.codewars.com/kata/5583090cbe83f4fd8c000051/solutions/javascript)

```javascript
function digitize(n) {
  return String(n).split("").map(Number).reverse();
}
```
