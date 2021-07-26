### [Problem](https://www.codewars.com/kata/51c8991dee245d7ddf00000e/javascript)

Complete the solution so that it reverses all of the words within the string passed in.

#### Example:

```
"The greatest victory is that which requires no battle" -->
"battle no requires which that is victory greatest The"
```

```javascript
function reverseWords(str) {
  return str; // reverse those words
}
// Sample Test:
describe("reverseWords", function () {
  it("should work for some examples", function () {
    Test.assertEquals(reverseWords("hello world!"), "world! hello");
    Test.assertEquals(
      reverseWords("yoda doesn't speak like this"),
      "this like speak doesn't yoda"
    );
    Test.assertEquals(reverseWords("foobar"), "foobar");
    Test.assertEquals(reverseWords("kata editor"), "editor kata");
    Test.assertEquals(
      reverseWords("row row row your boat"),
      "boat your row row row"
    );
  });
});
```

### [Solution](https://www.codewars.com/kata/51c8991dee245d7ddf00000e/solutions/javascript)

```javascript
function reverseWords(str) {
  return str.split(" ").reverse().join(" ");
}
```
