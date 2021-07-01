### [Problem](https://www.codewars.com/kata/5a3fe3dde1ce0e8ed6000097/javascript)

Given a year, return the century it is in.

The first century spans from the year 1 up to and including the year 100,  
the second - from the year 101 up to and including the year 200, etc.

#### Examples:

```
1705 --> 18
1900 --> 19
1601 --> 17
2000 --> 20
```

```javascript
function century(year) {
  // Finish this :)
  return;
}
// Sample Test:
describe("Tests", () => {
  it("test", () => {
    Test.assertEquals(century(1705), 18, "Testing for year 1705");
    Test.assertEquals(century(1900), 19, "Testing for year 1900");
    Test.assertEquals(century(1601), 17, "Testing for year 1601");
    Test.assertEquals(century(2000), 20, "Testing for year 2000");
    Test.assertEquals(century(89), 1, "Testing for year 89");
  });
});
```

### [Solution](https://www.codewars.com/kata/5a3fe3dde1ce0e8ed6000097/solutions/javascript)

```javascript
function century(year) {
  return Math.ceil(year / 100);
}
```
