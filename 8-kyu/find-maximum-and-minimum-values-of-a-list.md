### [Problem](https://www.codewars.com/kata/577a98a6ae28071780000989/javascript)

Your task is to make two functions, `max` and `min` (`maximum` and `minimum` in PHP and  
Python, `maxi` and `mini` in Julia) that take a(n) array/vector of integers `list` as  
input and outputs, respectively, the largest and lowest number in that array/vector.

#### Example:

```
max([4,6,2,1,9,63,-134,566]) returns 566
min([-52, 56, 30, 29, -54, 0, -110]) returns -110
max([5]) returns 5
min([42, 54, 65, 87, 0]) returns 0
```

```javascript
var min = function (list) {
  return list[0];
};
var max = function (list) {
  return list[0];
};
// Sample Test:
describe("Test", function () {
  it("Examples", function () {
    Test.assertEquals(min([-52, 56, 30, 29, -54, 0, -110]), -110);
    Test.assertEquals(min([42, 54, 65, 87, 0]), 0);
    Test.assertEquals(max([4, 6, 2, 1, 9, 63, -134, 566]), 566);
    Test.assertEquals(max([5]), 5);
  });
});
```

### [Solution](https://www.codewars.com/kata/577a98a6ae28071780000989/solutions/javascript)

```javascript
const min = (list) => Math.min(...list);
const max = (list) => Math.max(...list);
```
