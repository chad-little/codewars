### [Problem](https://www.codewars.com/kata/56bc28ad5bdaeb48760009b0/javascript)

It's pretty straightforward. Your goal is to create a function that removes  
the first and last characters of a string. You're given one parameter, the  
original string. You don't have to worry with strings with less than two  
characters.

```javascript
function removeChar(str) {
  //You got this!
}
// Sample Test:
describe("Tests", function () {
  Test.assertEquals(removeChar("eloquent"), "loquen");
  Test.assertEquals(removeChar("country"), "ountr");
  Test.assertEquals(removeChar("person"), "erso");
  Test.assertEquals(removeChar("place"), "lac");
});
```

### [Solution](https://www.codewars.com/kata/56bc28ad5bdaeb48760009b0/solutions/javascript)

```javascript
function removeChar(str) {
  return str.slice(1, -1);
}
```
